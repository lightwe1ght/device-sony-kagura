# Reference: <https://postmarketos.org/devicepkg>
pkgname=device-sony-kagura
pkgdesc="Sony Xperia XZ"
pkgver=0.1
pkgrel=0
url="https://postmarketos.org"
license="MIT"
arch="aarch64"
options="!check !archcheck"
depends="
	linux-sony-kagura
	mesa-dri-gallium
	mkbootimg
	postmarketos-base
"
makedepends="devicepkg-dev"
source="deviceinfo"

build() {
	devicepkg_build $startdir $pkgname
}

package() {
	devicepkg_package $startdir $pkgname
}

sha512sums="
0f6c45bffb9878b5471d49e0a03354b53d008b4b376bb4620d5eb26b3342be08f89cf7bfd8c41f774392f05fe3bd32c24ca3ace7cef85f11fa444620fbd71030  deviceinfo
"
