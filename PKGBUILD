# Maintainer: deb4sh <mpr-mail@b4sh.de>
pkgname=kubectx-bin
_pkgname=kubectx
pkgver=0.9.5
pkgrel=1
pkgdesc="Faster way to switch between clusters and namespaces in kubectl "
arch=('x86_64')
license=('Apache-2.0')
depends=()
makedepends=()
url="https://github.com/ahmetb/kubectx"
provides=('kubectx')
conflicts=('kubectx')

source=(
  https://github.com/ahmetb/kubectx/releases/download/v${pkgver}/kubectx_v${pkgver}_linux_${arch}.tar.gz  
)
sha256sums=(
  a2247ffd23e79f89abdd0e8173379d7172511f02a3f63c9936d3824e0dd60648
)

package() {
  install -Dm755 "kubectx" "$pkgdir/usr/local/bin/kubectx"
}
