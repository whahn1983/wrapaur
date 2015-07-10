NOTE: This github is no longer updated and is not the source of the latest wrapaur code.  The code is now maintained in the AUR using git.  Wrapaur 2.0.0-1 will be the last commit here.


wrapaur
=======

A simple pacman and AUR wrapper written in bash to help with everyday package tasks

Usage: wrapaur [OPTION]... [PACKAGE]...
(for multiple packages pass option each time; e.g. -i package1 -i package2)
  -a install from aur
  -c clean pacman cache with pacman -Sc, optimize pacman database, and clear .wrapaur folder
  -e check for updates from official repositories and aur and print available updates or email results if email is present in .wrapaurrc (add to cron or systemd timer to have email updates for new packages)
      note: email must be properly configured on system
  -i install from official repositories
  -l list installed packages with package count
  -m update pacman mirrorlist
  -n print the latest news from archlinux.org
  -o print aur comments for a specific package
  -q query information on a specific package
  -r remove a package with pacman -Rsn (for other removal options use pacman)
  -s search official repositories and aur
  -u update official repositories and aur
