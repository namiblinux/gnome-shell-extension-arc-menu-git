# Maintainer: Mohammadreza Abdollahzadeh < morealaz at gmail dot com >

pkgname=gnome-shell-extension-arc-menu-git
pkgver=31
pkgrel=1
pkgdesc='A GNOME shell extension designed to replace the standard menu found in GNOME 3.'
arch=(any)
url="https://gitlab.com/LinxGem33/Arc-Menu"
license=('GPL2')
depends=('gnome-shell>=3.18' 'gnome-menus')
makedepends=('git')
install='gnome-shell-extension.install'
source=("https://gitlab.com/LinxGem33/Arc-Menu/-/archive/v31-stable/Arc-Menu-v31-stable.zip")
sha256sums=('SKIP')

package() {
  cd Arc-Menu-v31-stable
  make DESTDIR="$pkgdir" INSTALL="system" install
}
# vim:set ts=2 sw=2 et:
