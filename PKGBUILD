# Contributor: William Hahn <whahn1983@gmail.com>

pkgname=wrapaur
pkgver=1.2
pkgrel=4
pkgdesc="A simple pacman and cower wrapper written in bash to help with everyday package tasks"
arch=('i686' 'x86_64')
url="https://github.com/whahn1983/wrapaur"
license=('GPL')
depends=('bash' 'cower' 'pacman' 'sudo' )
source=("wrapaur")
md5sums=('3eba572ab947fc6209ab1a05aac9eea2')

package() {
  install -Dm755 wrapaur "$pkgdir/usr/bin/wrapaur"
}
