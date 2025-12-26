pkgname=yt-dlp-config
pkgver=1
pkgrel=1
pkgdesc="System-wide yt-dlp config forcing Node.js JS runtime"
arch=('any')
depends=('yt-dlp' 'nodejs')
url="https://github.com/yt-dlp/yt-dlp"
license=('custom')
source=('config')
sha256sums=('28fbc6f470f8d8d340ff29a2623faf1403c5bb426ed80e7c64e765b737522680')
backup=('etc/yt-dlp/config')

package() {
    install -Dm644 "${srcdir}/config" "${pkgdir}/etc/yt-dlp/config"
}
