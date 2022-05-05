# Maintainer: Alexey Ugnichev <alexey.ugnichev@gmail.com>

pkgname=arch-bootstrap-current
_prefix="/opt"
pkgver=2022.05.01
pkgrel=1
epoch=
pkgdesc="Arch Linux's current bootstrap image"
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

sha256sums=('65d219da4a362ab1c3ee387a522060e91cf13dc558075a0b44a15e1f8c60f8de')

package() {
  cd "${srcdir}/"

  install -Dm644 "${_filename}" "${pkgdir}/${_prefix}/${pkgname}/${_filename}"
}

