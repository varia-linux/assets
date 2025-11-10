pkgname=varia-assets
pkgver=20251110
pkgrel=3
pkgdesc='Assets for Varia Linux'
arch=('x86_64')
license=('MIT')

pkgcommit='3f92e388603fe7a4bc38c33670f290f279075a19'
source=("https://github.com/varia-linux/assets/archive/$pkgcommit.tar.gz")
sha256sums=('9aba0b893135a271641b2dee43ef3f96984ccb57237f81b81536f1c837dd838a')

package() {
    install -d -m755 "$pkgdir/usr/share/backgrounds/varia"
    install -d -m755 "$pkgdir/usr/share/varia-linux"
    
    cp -r ${srcdir}/assets-${pkgcommit}/backgrounds "$pkgdir/usr/share/backgrounds/varia"
    cp -r ${srcdir}/assets-${pkgcommit}/assets "$pkgdir/usr/share/varia-linux"
    chmod -R 644 "${pkgdir}/usr/share/backgrounds/varia"
    chmod -R 644 "${pkgdir}/usr/share/varia-linux"
}