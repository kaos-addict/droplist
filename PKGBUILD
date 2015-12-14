pkgname=droplist
pkgver=0.1
pkgrel=1
pkgdesc="Simple drag and drop widget that onlys aims to list dropped files"
arch=('x86_64')
url="https://anapas.com"
license=('GPL')
depends=('yad')
source=(
        "droplist"
        "droplist.desktop"
        "droplist.png"
        )
sha512sums=('9a020d2b974ac741b432a75974c99916ac1907082d1c0718eea2340b2494563831786d859a019e35e74f140e8838a2e161c5ebbdf555a19a19d79ced3f620a26'
            'cce89733270cbda3dcfbc38073adbf6de3da57acc629524847edfa965ed2fd068e6c786ded33b980ba3a57377e9eacb581c80766453eecdfc0512a916bb53695'
            'ad687496091439052d64223155aa96f423d379e14ae4e64ff62e5d1812323cdde6ee3af85580b6f7869a146944fc99cec950459bd817c0d1da65f08826f2e716')

package() {
    cd "${srcdir}"
    install -Dm755 droplist "${pkgdir}/usr/bin/droplist"
    install -Dm755 droplist.png "${pkgdir}/usr/share/icons/droplist.png"
    install -Dm755 droplist.desktop "${pkgdir}/usr/share/applications/droplist.desktop"
}
