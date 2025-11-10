pkgname=varia-calamares
pkgver=1.0.1
pkgrel=1
pkgdesc='Calamares config for Varia Linux'
arch=('x86_64')
license=('MIT')

source=("https://github.com/varia-linux/varia-calamares/archive/22abd88c6d51d0c4b438ddd6868cef7005e0b931.tar.gz")
sha256sums=('5e2d37c54d7bc3d4f971afd40c6f83847078029b242a5f5ce15c3c127dd3f12d')

package() {
    install -d -m755 "$pkgdir/etc/calamares/"
    
    cp -r ${srcdir}/calamares "$pkgdir/etc/"
    chmod -R 644 "${pkgdir}/etc/calamares"
}