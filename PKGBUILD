# Maintainer: Marius Nestor <marius[at]softpedia[dot]com>
pkgname=ubuntu-touch-manager
pkgver=0.1.8.4
pkgrel=3
pkgdesc="Application for managing your Ubuntu Touch device."
url="https://launchpad.net/ubuntu-touch-manager"
arch=('any')
license=('GPL-3')
depends=('android-sdk-platform-tools' 'sudo' 'python2-imaging')
makedepends=('python2-distutils-extra')
# options='!emptydirs'
source=("https://launchpad.net/~majster-pl/+archive/ubuntu-touch-manager/+files/${pkgname}_${pkgver}.tar.gz")
md5sums=('85b4091f8840d5fefe00f43b4cb246ce')
install='ubuntu-touch-manager.install'

package() {
  cd $pkgname
  python2 setup.py install --root=${pkgdir}
}

