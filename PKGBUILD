pkgname=varia-assets
pkgver=20251110
pkgrel=1
pkgdesc='Assets for Varia Linux'
arch=('x86_64')
license=('MIT')

pkgcommit='22abd88c6d51d0c4b438ddd6868cef7005e0b931'
source=("https://github.com/varia-linux/assets/archive/$pkgcommit.tar.gz")
sha256sums=('5e2d37c54d7bc3d4f971afd40c6f83847078029b242a5f5ce15c3c127dd3f12d')

package() {
    install -d -m755 "$pkgdir/usr/share/backgrounds/varia"
    install -d -m755 "$pkgdir/usr/share/varia-linux"
    
    cp -r ${srcdir}/${pkgname}-${pkgcommit}/backgrounds "$pkgdir/usr/share/backgrounds/varia"
    cp -r ${srcdir}/${pkgname}-${pkgcommit}/assets "$pkgdir/usr/share/varia-linux"
    chmod -R 644 "${pkgdir}/etc/backgrounds/varia"
    chmod -R 644 "${pkgdir}/etc/varia-linux"
}