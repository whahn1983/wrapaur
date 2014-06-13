# Contributor: William Hahn <whahn1983@gmail.com>

pkgname=wrapaur
pkgver=1.6.3
pkgrel=1
pkgdesc="A simple pacman and cower wrapper written in bash to help with everyday package tasks"
arch=('i686' 'x86_64')
url="https://github.com/whahn1983/wrapaur"
license=('GPL')
depends=('bash' 'cower' 'pacman' 'sudo' )
optdepends=('reflector: required to update mirrorlist')
source=("wrapaur")
md5sums=('c6506c05d6587e9cb37330c4d94b2f7e')

package() {
  install -Dm755 wrapaur "$pkgdir/usr/bin/wrapaur"
}
