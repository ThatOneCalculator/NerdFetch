# Maintainer: ThatOneCalculator (Kainoa Kanter) <kainoakanter@gmail.com>
pkgname="nerdfetch"
pkgver=1
pkgrel=1
pkgdesc="A POSIX fetch using NerdFonts"
arch=('any')
url="https://github.com/ThatOneCalculator/NerdFetch"
license=('GPL')
makedepends=('git')
source=("git+https://github.com/ThatOneCalculator/NerdFetch")
noextract=()
md5sums=('SKIP')

pkgver() {
	cd NerdFetch
	printf "r%s.%s" "$(git rev-list --count HEAD)" "$(git rev-parse --short HEAD)"
}

prepare() {
    cd NerdFetch
}

package() {
    install -Dm755 "$srcdir"/NerdFetch/nerdfetch "$pkgdir/usr/bin/nerdfetch"
    install -Dm644 "$srcdir"/NerdFetch/README.md "$pkgdir/usr/share/doc/$pkgname"
}