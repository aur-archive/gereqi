# Maintainer: Mike Shade <mshade@mshade.org>
pkgname=gereqi
pkgver=0.4.2
pkgrel=4
pkgdesc="Gereqi (pronounced: geh-reh-kee) is a music organiser and player. Gereqi is a clone of the now dead Amarok-1.4 and aims to replace Amarok's features and interface."
arch=("i686" "x86_64")
url="http://code.google.com/p/gereqi/"
license=('GPLv3')
groups=()
depends=("python2" "mutagen" "cddb-py" "python2-pyinotify" "pyqt" "gstreamer0.10-python" "gstreamer0.10-bad-plugins" "gstreamer0.10-good-plugins" "gstreamer0.10-ugly-plugins")
makedepends=()
conflicts=("gereqi-git")
replaces=()
backup=()
options=()
install=
changelog=
source=(http://gereqi.googlecode.com/files/gereqi-0.4.2.tar.gz)
noextract=()
md5sums=('41a8e78e721f9aa0152af4815ffb6d00')

package() {
  cd "$srcdir/$pkgname-$pkgver"
  python2 setup.py install --root="$pkgdir"

}
