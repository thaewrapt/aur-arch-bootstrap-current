# Maintainer: Alexey Ugnichev <alexey.ugnichev@gmail.com>

pkgname=arch-bootstrap-current
_prefix="/opt"
pkgver=2020.04.01
pkgrel=1
epoch=
pkgdesc="Arch Linux's current boostrap image"
arch=("x86_64")
url="https://www.archlinux.org/download/"
license=('GPL')
groups=()
depends=()
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
_filename="${pkgname}.tar.gz"
source=("${_filename}"::"https://mirrors.kernel.org/archlinux/iso/${pkgver}/archlinux-bootstrap-${pkgver}-${CARCH}.tar.gz")
noextract=("${_filename}")

sha256sums=('0ba0ac70aee95a8c25353fefcddd95f24c9c139a522a260aa57391913dcec295')

package() {
  cd "${srcdir}/"

  install -Dm644 "${_filename}" "${pkgdir}/${_prefix}/${pkgname}/${_filename}"
}

