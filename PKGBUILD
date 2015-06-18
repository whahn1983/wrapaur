# Contributor: William Hahn <bill@hahn3.com>

pkgname=wrapaur
pkgver=2.0.0
pkgrel=1
pkgdesc="A simple pacman and AUR wrapper written in bash to help with everyday package tasks"
arch=('i686' 'x86_64')
url="https://aur.archlinux.org/wrapaur.git"
license=('GPL')
depends=('bash' 'coreutils' 'curl' 'grep' 'gawk' 'sed' 'git' 'pacman' 'sudo')
optdepends=('s-nail: required for mail notifications')
source=("wrapaur")
md5sums=('3c60184ae4522e4bb79b13cf2bdede05')

package() {
  install -Dm755 wrapaur "$pkgdir/usr/bin/wrapaur"
}
