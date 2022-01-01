# Maintainer: Jonas Strassel <info@jonas-strassel.de>

pkgname=zeit
pkgver=0.0.4
pkgrel=1
arch=('x86_64')
url="https://github.com/mrusme/$pkgname"
license=('GPL')
pkgdesc='Zeit, erfassen. A command line tool for tracking time spent on activities. '

source=(${pkgname}-${pkgver}.tar.gz::${url}/releases/download/${pkgver}/zeit_linux_amd64.tar.gz)
md5sums=('565d82b16bd01ff7d1df1da3a8088fcc')

package() {
  install -D ${pkgname} ${pkgdir}/usr/bin/${pkgname}
}
