# Maintainer: jnats <jnats[at]salyut[dot]one>
# Maintainer: matt <mdc[at]bucknell[dot]edu>

# Arch credits:
# Pierre Schmitz <pierre@archlinux.de>

pkgname=crystal-keyring
pkgver=20220729
pkgrel=1
pkgdesc='Crystal Linux PGP keyring'
arch=('any')
url="https://github.com/crystal-linux/${pkgname}"
license=('GPL')
install="${pkgname}.install"
depends=('make')
source=("git+$url")
sha256sums=('SKIP')
package() {
  cd "${srcdir}/${pkgname}"
  make PREFIX=/usr DESTDIR=${pkgdir} install
}
