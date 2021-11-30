# Maintainer: Ruslan Sergin <ruslan.sergin@gmail.com>
pkgname=arcolinux-logout
pkgver=21.07_02
pkgrel=2
pkgdesc="Beautiflul ArcoLinux logout screen"
url="https://github.com/arcolinux/arcolinux-logout"
arch=('x86_64')
depends=('python3' 'python-cairo')
license=('GPL3')
source=("git+https::/github.com/git-fal7/arcolinux-logout")
md5sums=('SKIP')

package () {
    mkdir -p "${pkgdir}" 
    mv "${srcdir}/${pkgname}/"{usr,etc} "${pkgdir}/"
    mv "${srcdir}/${pkgname}/LICENSE" "${pkgdir}/usr/share/arcologout"
    mv "${srcdir}/${pkgname}/README.md" "${pkgdir}/usr/share/arcologout"
}
