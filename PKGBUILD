# Maintainer: Alexey Ugnichev <alexey.ugnichev@gmail.com>

pkgname=arch-bootstrap-current
_prefix="/opt"
pkgver=2025.06.01
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

sha256sums=('84bb1c26aed40e6797770f788186b5011970e670cb4b0c8519b6d6884c0c8e2f')

package() {
  cd "${srcdir}/"

  install -Dm644 "${_filename}" "${pkgdir}/${_prefix}/${pkgname}/${_filename}"
}

