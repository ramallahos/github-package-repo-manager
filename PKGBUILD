# Maintainer: Safwan Nayeem Yousuf <safwannayeemyousuf.com>
pkgname=github-package-repo-manager
pkgver=1
pkgrel=1
pkgdesc="Converts multiple lines to a line and vice versa."
arch=('any')
url="https://github.com/ramallahos/$pkgname"
license=('MIT')
depends=('yad')
makedepends=('coreutils')
backup=('etc/pacman.conf')
source=("$pkgname::git+$url.git")
sha256sums=('SKIP')

package() {
    cd "$pkgname"
    install -Dm755 "$pkgname" "$pkgdir/usr/bin/$pkgname"
}
