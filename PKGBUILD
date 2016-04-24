#Maintainer: Alex Gajewski <apagajewski@gmail.com>

_pkgname=ice-ssb
pkgname=ice-ssb
pkgver=5.0.10
pkgrel=1
pkgdesc='ICE SSB'
arch=(any)
url='http://github.com/Apricity-OS/ice-ssb'
license=(GPL)
depends=("python-requests" "python-beautifulsoup4" "python2" "pygtk" "python2-gobject")
source=("ice-ssb.tar.gz")
sha256sums=('d6a0e69e0acd7d7d21495a39e36c2b9a161742be80d75b115f612ee7f1f5395c')
install=ice-ssb.install

package() {
	mkdir -p "${pkgdir}/usr/share/applications"
	mkdir -p "${pkgdir}/usr/share/pixmaps"
	mkdir -p "${pkgdir}/usr/bin"
	cp -f "${srcdir}/ice-ssb/ice" "${pkgdir}/usr/bin"
	cp -f "${srcdir}/ice-ssb/ice-firefox" "${pkgdir}/usr/bin"
	cp -f "${srcdir}/ice-ssb/ice.desktop" "${pkgdir}/usr/share/applications"
	cp -f "${srcdir}/ice-ssb/ice.png" "${pkgdir}/usr/share/pixmaps"
}
