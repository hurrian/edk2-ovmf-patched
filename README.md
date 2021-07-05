# edk2-ovmf-patched
[edk2-ovmf](https://archlinux.org/packages/extra/any/edk2-ovmf/) from Arch Linux, PKGBUILD patched for stealth.
Best used with [qemu-patched](https://github.com/hurrian/qemu-patched).

# Install
1. Clone
1. Change string values in ``edk2.patch`` to be unique
1. Build with dependencies ``makepkg -s``
1. Install with pacman ``pacman -U edk2-ovmf-patched-<version>.pkg.tar.zst``

# Usage
Select the desired firmware in virt-manager.
