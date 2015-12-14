pkgname=droplist
pkgver=0.1
pkgrel=1
pkgdesc="Simple drag and drop widget that onlys aims to list dropped files"
arch=('x86_64')
url="https://anapas.com"
license=('GPL')
depends=('yad')
source=("droplist")
sha512sums=('9a020d2b974ac741b432a75974c99916ac1907082d1c0718eea2340b2494563831786d859a019e35e74f140e8838a2e161c5ebbdf555a19a19d79ced3f620a26')

package() {
    cd "${srcdir}"
    install -Dm755 droplist "${pkgdir}/usr/bin/droplist"
    install -Dm755 droplist.png "${pkgdir}/usr/share/icons/droplist.png"
    install -Dm755 droplist.desktop "${pkgdir}/usr/share/applications/droplist.desktop"
}
