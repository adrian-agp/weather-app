pkgname=weather-app
pkgver=1.0
pkgrel=1
pkgdesc="Una aplicación de clima simple"
arch=('any')
url="https://github.com/adrian-agp/weather-app"
license=('MIT')
depends=('python' 'tk' 'python-geopy' 'python-requests')
source=("${pkgname}-${pkgver}.tar.gz::https://github.com/adrian-agp/weather-app/releases/download/1.0/${pkgname}-${pkgver}.tar.gz")
sha256sums=('4208162ED3E415815AF584C29035C839464B24FA973D3ADEA4CD7EAAA7A86BEC')
 
package() {
    cd "${srcdir}/${pkgname}-${pkgver}"
    python setup.py install --root="${pkgdir}" --optimize=1
}

