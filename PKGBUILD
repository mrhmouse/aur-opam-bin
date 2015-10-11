# Maintainer: Jordan Brown <mrhmouse@gmail.com>

pkgname=opam-bin
pkgver=1.2.2
pkgrel=1
pkgdesc="OCaml Package Manager"
arch=('i686' 'x86_64' 'armv7l')
url="http://opam.ocaml.org"
license=('GPL')
depends=('ocaml' 'aspcud')
source=(https://github.com/ocaml/opam/releases/download/${pkgver}/opam-${pkgver}-${arch}-Linux)
md5sums=('2759791a25ba4bfe528915d88abc221a')

package() {
  mkdir -p "${pkgdir}/usr/bin"
  mv "opam-${pkgver}-${arch}-Linux" "${pkgdir}/usr/bin/opam"
}

# vim:set ts=2 sw=2 et:
