# Maintainer: Jakub Schmidtke <sjakub-at-gmail-dot-com>

pkgname=android-armv7a-eabi-system-image-16
pkgver=4.1.1_r02
pkgrel=1
pkgdesc='Android ARM EABI v7a System Image, API-16'
arch=('any')
url="http://developer.android.com/sdk/index.html"
license=('custom')
depends=('android-platform-16')
options=('!strip')
source=("http://dl-ssl.google.com/android/repository/sysimg_armv7a-16_r02.zip")
sha1sums=('62e269c79880b0b4be410ab3e62cdd235f02ccd8')

package() {
  mkdir -p "${pkgdir}/opt/android-sdk/system-images/android-16/"
  mv "${srcdir}/armeabi-v7a" "${pkgdir}/opt/android-sdk/system-images/android-16/armeabi-v7a"

  chmod -R ugo+rX "${pkgdir}/opt"
}
