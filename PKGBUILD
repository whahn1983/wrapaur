# Contributor: William Hahn <bill@hahn3.com>

pkgname=wrapaur
pkgver=2.0.0
pkgrel=1
pkgdesc="A simple pacman and AUR wrapper written in bash to help with everyday package tasks"
arch=('i686' 'x86_64')
url="https://aur.archlinux.org/wrapaur.git"
license=('GPL')
depends=('bash' 'curl' 'grep' 'gawk' 'sed' 'git' 'pacman' 'sudo')
optdepends=('reflector: required to update mirrorlist' 's-nail: required for email notifications')
source=("wrapaur")
md5sums=('c2314fdff31e541515191e8291f95760')

package() {
  install -Dm755 wrapaur "$pkgdir/usr/bin/wrapaur"
}
