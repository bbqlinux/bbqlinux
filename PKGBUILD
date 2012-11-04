# Maintainer: Daniel Hillenbrand <codeworkx@bbqlinux.org>

pkgname=bbqlinux
pkgver=20121104
pkgrel=1
pkgdesc="BBQLinux meta package"
arch=('any')
depends=('bbqlinux-artwork' 'bbqlinux-config' 'bbqlinux-themes-slim')
url="https://github.com/bbqlinux/bbqlinux"
license=('GPL')
groups=('bbqlinux')

package() {
    cd "$pkgdir"
    mkdir -p etc

    install -Dm700 "$srcdir/etc/bbqlinux-version" etc/bbqlinux-version
}
