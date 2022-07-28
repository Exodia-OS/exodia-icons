#
# Maintainer: Mahmoud Mohamed (Ozil) <mmsaeed509@gmail.com> , <https://github.com/mmsaeed509>
#

pkgname=exodia-icons
pkgver=1.0
pkgrel=1
pkgdesc="Icons For Exodia OS"
arch=('any')
url="https://github.com/Exodia-OS/exodia-icons"
license=('GPL3')

prepare() {

	cp -af ../icons/. ${srcdir}

}

package() {

	local icons_dir=${pkgdir}/usr/share/icons
	mkdir -p "$icons_dir"
	cp -r ${srcdir}/* "$icons_dir"

}
