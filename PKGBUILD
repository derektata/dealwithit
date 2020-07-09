# Maintainer: Derek Tata <derekjtata@gmail.com>
pkgname=dealwithit
pkgver=r11.868bb18
pkgrel=1
pkgdesc="A utility to print shades in the terminal, deal with it."
arch=('x86_64')
url="https://github.com/derektata/dealwithit"
license=('GPL')
makedepends=('git')
source=("git+$url")
md5sums=('SKIP')

package() {
	echo "$srcdir/$pkgname"
		cd "$srcdir/$pkgname"
	install -Dm755 dealwithit.sh "$pkgdir/usr/bin/dealwithit"
	install -Dm644 README.md "$pkgdir/usr/share/doc/$pkgname"
}
