# Maintainer: mutlu_inek@yahoo.de

pkgname=pysheng
pkgver=0.1
pkgrel=2
pkgdesc="CLI and GUI program to download pages from Google Books as PNG images"
arch=(i686 x86_64)
url="https://code.google.com/p/pysheng/"
license=('GPL')
depends=('python2')
makedepends=()
optdepends=('python2-reportlab: GUI'
	    'pygtk: GUI')
provides=()
conflicts=()
replaces=()
options=()
source=(http://pysheng.googlecode.com/files/$pkgname-$pkgver.tgz)
md5sums=('058d309f36ced4bdcbc7525d1d1fb57f')

package() {
   cd $pkgname-$pkgver
   python2 setup.py install --root="$pkgdir/" --optimize=1
}

