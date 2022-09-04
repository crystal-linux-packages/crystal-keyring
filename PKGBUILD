# Maintainer: TWljaGFsIFMuIDxtaWNoYWxAZ2V0Y3J5c3QuYWw+         | base64 -d
# Maintainer: TWF0dCBDLiA8bWF0dEBnZXRjcnlzdC5hbD4=             | base64 -d
# Credit:     UGllcnJlIFNjaG1pdHogPHBpZXJyZUBhcmNobGludXguZGU+ | base64 -d

pkgname=crystal-keyring
pkgver=20220729
pkgrel=1
pkgdesc='Crystal Linux PGP keyring'
arch=('any')
url="https://github.com/crystal-linux/${pkgname}"
license=('GPL')
install="$pkgname.install"
makedepends=('make' 'git')
source=("git+$url")
sha256sums=('SKIP')

package() {
  cd "$srcdir/$pkgname"
  make PREFIX=/usr DESTDIR="$pkgdir" install
}
