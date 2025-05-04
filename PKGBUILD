# Maintainer: Jonas Strassel <info@jonas-strassel.de>

pkgname=zeit
pkgver=v0.0.9
pkgver_number=0.0.9
pkgrel=3
arch=('x86_64' 'aarch64')
url="https://github.com/mrusme/$pkgname"
license=('GPL')
pkgdesc='Zeit, erfassen. A command line tool for tracking time spent on activities. '

source_x86_64=(${pkgname}-${pkgver}.tar.gz::${url}/releases/download/${pkgver}/zeit_${pkgver_number}_linux_amd64.tar.gz)
md5sums_x86_64=('49ad3ddaf9f6e3f1851173e05307eded')

source_aarch64=(${pkgname}-${pkgver}.tar.gz::${url}/releases/download/${pkgver}/zeit_${pkgver_number}_linux_arm64.tar.gz)
md5sums_aarch64=('49ad3ddaf9f6e3f1851173e05307eded')

package() {
  install -D ${pkgname} ${pkgdir}/usr/bin/${pkgname}
}
