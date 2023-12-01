# Maintainer: thesting <fxcw_vacilon@slmail.me>
# Contributor: deb4sh <github@b4sh.de>
pkgname=k9s-bin
_pkgname=k9s
pkgver=0.28.2
pkgrel=1
pkgdesc="Kubernetes CLI To Manage Your Clusters In Style!"
arch=('amd64')
license=('Apache-2.0')
depends=()
makedepends=()
url="https://github.com/derailed/k9s"
provides=('k9s')
conflicts=('k9s')

source=(
  https://github.com/derailed/k9s/releases/download/v${pkgver}/k9s_Linux_amd64.tar.gz
)
sha512sums=(
  25206c16eaaa08357105e98e0a76f31a280c13968fa7ca4490f35234f2baaf6de549aab554d32c9d38480936e1b6a091cee259fbb048a5855715700a153bf01e
)

package() {
  install -Dm755 "k9s" "$pkgdir/usr/local/bin/k9s"
}
