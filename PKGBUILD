pkgname=zfs-dkms-hook
pkgver=0.1
pkgrel=1
arch=('any')

package() {

  install -D -m 644 -t \
      "${pkgdir}/usr/share/libalpm/hooks" \
      "${srcdir}/60-dkms-install-zfs.hook"
      

  install -D -m 755 -t \
      "${pkgdir}/usr/bin" \
      "${srcdir}/dkms-install-zfs"
}

