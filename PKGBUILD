pkgname=varia-calamares
pkgver=1.0.0
pkgrel=1
pkgdesc='Calamares config for Varia Linux'
arch=('x86_64')
license=('MIT')

source=("./calamares/")

package() {
    install -d -m755 "$pkgdir/etc/calamares/"
    
    cp -r calamares/* "$pkgdir/etc/calamares/"
}