# Maintainer: Vinzenz Vietzke <aur at vinzv.de>

pkgname=manjaro-clean-colored-wallpapers
pkgver=1
pkgrel=1
pkgdesc="A pack of unofficial wallpapers for Arch derivate Manjaro Linux"
arch=('i686' 'x86_64')
url="http://mirror.vinzv.de/manjaro/aur/pkg-src/"
license=('CC-BY-SA 3.0')
#depends=()
#makedepends=()
#options=()
#provides=()
conflicts=(manjaro-artwork-extra)
groups=('wallpaper')
install=wallpapers.install
source=(http://mirror.vinzv.de/manjaro/aur/pkg-src/${pkgname}.tar.bz2)
md5sums=('d947b6b59c702ac41886bebe958eb527')

build() {
install -d ${pkgdir}/usr/share/manjaro-clean-colored-wallpapers/
cp -r ${pkgname}/* ${pkgdir}/usr/share/${pkgname}/
}

