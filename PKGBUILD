# Maintainer: Alex Tokarev <aleksator at gmail>
pkgname=xcursor-arch-cursor-complete
pkgver=19.11.2017
pkgrel=1
pkgdesc="Complete version of Arch Cursor Simple theme supplying missing cursors."
arch=('any')
url="https://github.com/aleksator/arch-cursor-complete"
license=('custom:cc-by-4.0')
source=("https://github.com/aleksator/arch-cursor-complete/files/1485806/ArchCursorComplete.tar.gz")
md5sums=('2f55afa65a228c84eac66cf6c8b6be3e')

package() {
    install -d -m755 "${pkgdir}/usr/share/icons"
    cp -dr ArchCursorComplete "${pkgdir}/usr/share/icons"
}
