# Maintainer: Sébastien Luttringer

pkgname=aurbot-git
pkgver=$(git log --pretty=format:''|wc -l)
pkgrel=1
pkgdesc='AUR Builder Bot'
arch=('any')
url='https://github.com/seblu/aurbot'
license=('GPL2')
backup=('etc/aurbot.conf')
depends=('python')
optdepends=('devtools')
install=aurbot.install

package() {
  cd "$startdir"
  install -Dm755 aurbot "$pkgdir/usr/bin/aurbot"
}

# vim:set ts=2 sw=2 et:
