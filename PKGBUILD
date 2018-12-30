# Maintainer: Alexey Ugnichev <alexey.ugnichev@gmail.com>

pkgname=arch-bootstrap-current
_prefix="/opt"
pkgver=2018.11.01
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

sha256sums=('2f75491c9fff098261b42dcb71e3426948ad150e5260063301e2507eba2f2ebe')

package() {
  cd "${srcdir}/"

  install -Dm644 "${_filename}" "${pkgdir}/${_prefix}/${pkgname}/${_filename}"
}

