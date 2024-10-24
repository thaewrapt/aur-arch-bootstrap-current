# Maintainer: Alexey Ugnichev <alexey.ugnichev@gmail.com>

pkgname=arch-bootstrap-current
_prefix="/opt"
pkgver=2024.10.01
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
_filename="${pkgname}.tar.zst"
source=("${_filename}"::"https://mirrors.kernel.org/archlinux/iso/${pkgver}/archlinux-bootstrap-${pkgver}-${CARCH}.tar.zst")
noextract=("${_filename}")

sha256sums=('af1396ce99ef3b3551b550d87b3822d533ec5af9788846243ee3114905d0bfb6')

package() {
  cd "${srcdir}/"

  install -Dm644 "${_filename}" "${pkgdir}/${_prefix}/${pkgname}/${_filename}"
}

