pkgname=varia-calamares
pkgver=1.0.0
pkgrel=1
pkgdesc='Calamares config for Varia Linux'
arch=('x86_64')
license=('MIT')

source=("https://github.com/varia-linux/varia-calamares/archive/874295fd4e13846f4a473122bf86e22f933cc65b.tar.gz")
sha256sums=('bc85f7350964e6760d6eebf4fa1d0f86f626ffd7cad36273d49673632d67eeff')

package() {
    install -d -m755 "$pkgdir/etc/calamares/"
    
    cp -r calamares/* "$pkgdir/etc/calamares/"
}