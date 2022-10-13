# Maintainer:  echo -n 'TWF0dCBDLiA8bWF0dEBnZXRjcnlzdC5hbD4='     | base64 -d
# Contributor: echo -n 'TWljaGFsIFMuIDxtaWNoYWxAZ2V0Y3J5c3QuYWw+' | base64 -d
# Contributor: echo -n 'Um9iaW4gQy4gPHJjYW5kYXVAZ2V0Y3J5c3QuYWw+' | base64 -d

pkgname=crystal-keyring
pkgver=2022.10.12
pkgrel=1
pkgdesc='Crystal Linux PGP keyring'
arch=('any')
url="https://github.com/crystal-linux/${pkgname}"
license=('GPL')
install="${pkgname}.install"
source=("${pkgname}-${pkgver}::${url}/archive/${pkgver}.tar.gz")
sha256sums=('d7da9302c0404ef31d726d994d49c9e0df14d7c8248525658b152abdacd91535')

package() {
    cd "${srcdir}/${pkgname}-${pkgver}"
    make PREFIX=/usr DESTDIR="${pkgdir}" install
}
