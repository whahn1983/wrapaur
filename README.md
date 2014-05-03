wrapaur
=======

A simple pacman and cower wrapper written in bash to help with everyday package tasks

Usage: wrapaur [OPTION]... [PACKAGE]...
(for multiple packages pass option each time; e.g. -i package1 -i package2)
  -a install from aur
  -c clean pacman cache with pacman -Sc, optimize pacman database, and clear .wrapaur folder
  -e check for updates from official repositories and aur and print available updates or email results if email is present in .wrapaurrc (add to cron or systemd timer to have email updates for new packages)
      note: email must be properly configured on system
  -i install from official repositories
  -l list installed packages with package count
  -m update pacman mirrorlist wth reflector (default options: top 200 http servers sorted by download rate)
  -q query information on a specific package
  -r remove a package with pacman -Rsn (for other removal options use pacman)
  -s search official repositories and aur
  -u update official repositories and aur
