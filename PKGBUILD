# Maintainer: Tobias Neumann <mail at tobias dash neumann dot eu>

pkgname=r-labeling
pkgver=0.1
pkgrel=3
pkgdesc="Provides a range of axis labeling algorithms"
arch=('i686' 'x86_64')
url="http://cran.r-project.org/web/packages/labeling/index.html"
license=('')
depends=('r')
source=(http://cran.r-project.org/src/contrib/labeling_$pkgver.tar.gz)

package() {
 mkdir -p $pkgdir/usr/lib/R/library
 cd $srcdir
 R CMD INSTALL -l $pkgdir/usr/lib/R/library ./labeling
}
md5sums=('8ec4a66a5432110f295a2c2a8eb69e81')
