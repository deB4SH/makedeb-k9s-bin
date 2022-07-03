# Maintainer: thesting <fxcw_vacilon@slmail.me>
pkgname=k9s-bin
_pkgname=k9s
pkgver=0.25.21
pkgrel=1
pkgdesc="Kubernetes CLI To Manage Your Clusters In Style!"
arch=('x86_64')
license=('Apache-2.0')
depends=()
makedepends=()
url="https://github.com/derailed/k9s"
provides=('k9s')
conflicts=('k9s')

source=(
  https://github.com/derailed/k9s/releases/download/v${pkgver}/k9s_Linux_x86_64.tar.gz
)
sha512sums=(
  efdf2c025cd0e176257460c461976614bfdc149e60f631e3cb41dad2f1a58bdf3293d07eb68fe3f201f1daf30da2a0129d1e53ef49e20ff10ae8dc816e95afde
)

package() {
  install -Dm755 "k9s" "$pkgdir/usr/local/bin/k9s"
}
