pkgname=droplist
pkgver=0.1
pkgrel=1
pkgdesc="Simple drag and drop widget that onlys aims to list dropped files"
arch=('x86_64')
url="https://anapas.com"
license=('GPL')
depends=('yad')
source=("droplist")
sha512sums=('')

package() {
    cd "${srcdir}"
    install -Dm755 droplist "${pkgdir}/usr/bin/droplist"
    install -Dm755 droplist.png "${pkgdir}/usr/share/icons/droplist.png"
    install -Dm755 droplist.desktop "${pkgdir}/usr/share/applications/droplist.desktop"
}
