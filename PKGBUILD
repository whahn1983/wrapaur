# Contributor: William Hahn <whahn1983@gmail.com>

pkgname=wrapaur
pkgver=1.6.1
pkgrel=1
pkgdesc="A simple pacman and cower wrapper written in bash to help with everyday package tasks"
arch=('i686' 'x86_64')
url="https://github.com/whahn1983/wrapaur"
license=('GPL')
depends=('bash' 'cower' 'pacman' 'sudo' )
optdepends=('reflector: required to update mirrorlist')
source=("wrapaur")
md5sums=('e8490ca742dd00d5c88b4ecd746a5424')

package() {
  install -Dm755 wrapaur "$pkgdir/usr/bin/wrapaur"
}
