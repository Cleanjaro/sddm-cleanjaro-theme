# Maintainer: David Spink <yorper_protonmail.com>
# Theme based from https://github.com/vinceliuice/

pkgname=sddm-cleanjaro-theme
pkgver=1
pkgrel=1.2
pkgdesc='SDDM theme for Cleanjaro'
arch=('x86_64')
url="https://github.com/Cleanjaro/sddm-cleanjaro-theme"
license=('GPL3')
depends=('qt5-quickcontrols' 'sddm')
source+=("git+$url.git")
sha256sums=('SKIP')

package() {
    mkdir -p "${pkgdir}/usr/share/sddm/themes"
    cp -r "${srcdir}/sddm-cleanjaro-theme" "${pkgdir}/usr/share/sddm/themes/cleanjaro"
}

