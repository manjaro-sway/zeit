# Maintainer: Jonas Strassel <info@jonas-strassel.de>

pkgname=zeit
pkgver=0.0.4
pkgrel=2
arch=('x86_64' 'aarch64')
url="https://github.com/mrusme/$pkgname"
license=('GPL')
pkgdesc='Zeit, erfassen. A command line tool for tracking time spent on activities. '

source_x86_64=(${pkgname}-${pkgver}.tar.gz::${url}/releases/download/${pkgver}/zeit_linux_amd64.tar.gz)
md5sums_x86_64=('565d82b16bd01ff7d1df1da3a8088fcc')

source_aarch64=(${pkgname}-${pkgver}.tar.gz::${url}/releases/download/${pkgver}/zeit_linux_arm64.tar.gz)
md5sums_aarch64=('145b35f73580a8a3abe887b4d9edbf97')

package() {
  install -D ${pkgname} ${pkgdir}/usr/bin/${pkgname}
}
