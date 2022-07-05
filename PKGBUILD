# Maintainer: Jonas Strassel <info@jonas-strassel.de>

pkgname=zeit
pkgver=v0.0.6
pkgver_number=0.0.6
pkgrel=3
arch=('x86_64' 'aarch64')
url="https://github.com/mrusme/$pkgname"
license=('GPL')
pkgdesc='Zeit, erfassen. A command line tool for tracking time spent on activities. '

source_x86_64=(${pkgname}-${pkgver}.tar.gz::${url}/releases/download/${pkgver}/zeit_${pkgver_number}_linux_amd64.tar.gz)
md5sums_x86_64=('12468fd10159f9e4c58ac81bda5f8607')

source_aarch64=(${pkgname}-${pkgver}.tar.gz::${url}/releases/download/${pkgver}/zeit_${pkgver_number}_linux_arm64.tar.gz)
md5sums_aarch64=('92289a319b4fa5483ddfadfa887930dd')

package() {
  install -D ${pkgname} ${pkgdir}/usr/bin/${pkgname}
}
