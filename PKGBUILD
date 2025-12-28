# Maintainer: Serhii Hordiienko <phrippy2@gmail.com>

pkgname=yt-dlp-config
pkgver=20251228
pkgrel=1
pkgdesc="System-wide yt-dlp config forcing Node.js JS runtime"
arch=('any')
depends=('yt-dlp' 'nodejs')
url="https://github.com/yt-dlp/yt-dlp"
license=('custom')
source=('config')
sha256sums=('6e65e2ea21997faa1bb886bf019a1f2a6f978372748ccad009f0f31de0e7816a')
backup=('etc/yt-dlp/config')

package() {
    install -Dm644 "${srcdir}/config" "${pkgdir}/etc/yt-dlp/config"
}
