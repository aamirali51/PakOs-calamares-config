# Maintainer: Erik Dubois <erik.dubois@gmail.com>
pkgname=carli-calamares-config
_destname1="/etc"
_destname2="/etc"
_destname3="/etc"
_destname4="/etc"
pkgver=22.06
pkgrel=01
pkgdesc="calamares for carli"
arch=('any')
url="https://github.com/arcolinuxiso"
license=('GPL3')
makedepends=('git')
depends=()
conflicts=()
provides=("${pkgname}")
options=(!strip !emptydirs)
source=(${pkgname}::"git+${url}/${pkgname}")
sha256sums=('SKIP')
package() {
	install -dm755 ${pkgdir}${_destname1}
	cp -r ${srcdir}/${pkgname}${_destname1}/* ${pkgdir}${_destname1}
}
