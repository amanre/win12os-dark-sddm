pkgname=win12os-dark-sddm-git
_pkgname=win12os-dark-sddm
_destname1="/usr/share/sddm/themes/"
pkgver=1
pkgrel=01
pkgdesc="sddm-theme "
arch=('any')
url="https://github.com/amanre/win12os-dark-sddm"
license=('GPL3')
makedepends=('git')
depends=('bash')
provides=("${pkgname}")
options=(!strip !emptydirs)
source=(${_pkgname}::"git+https://github.com/amanre/${_pkgname}.git")
sha256sums=('SKIP')
package() {

	install -dm755 ${pkgdir}${_destname1}
	cp -r  ${srcdir}/${_pkgname}${_destname1}* ${pkgdir}${_destname1}
}
