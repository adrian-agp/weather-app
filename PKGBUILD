pkgname=weather-app
pkgver=1.0
pkgrel=1
pkgdesc="Una aplicación de clima simple"
arch=('any')
url="URL_DEL_PROYECTO"
license=('MIT')
depends=('python' 'tk' 'geopy' 'timezonefinder' 'requests' 'Pillow')
source=("${pkgname}-${pkgver}.tar.gz::https://github.com/adrian-agp/${pkgname}-${pkgver}.tar.gz")
sha256sums=('SHA256_DEL_ARCHIVO')
 
package() {
    cd "${srcdir}/${pkgname}-${pkgver}"
    python setup.py install --root="${pkgdir}" --optimize=1
}

