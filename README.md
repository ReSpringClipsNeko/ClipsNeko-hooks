# clipsneko-hooks

Pacman hooks for setting up system identification files and other features of ClipsNeko Linux.

Modified from CachyOS's ![repository](https://github.com/CachyOS/cachyos-hooks)

File name | Description
:--- | :---
clipsneko-branding | Fixes files like `os-release`, `lsb-release`, `issues` for ClipsNeko Linux.
clipsneko-branding.hook | Runs `clipsneko-branding` script after the `clipsneko-hooks` package is updated.
clipsneko-plymouth-initramfs.hook | Replaces plymouth script to update initrd with ``update-initramfs``
clipsneko-reboot-required | Notifies user to reboot after essential system files have been updated.
clipsneko-reboot-required.hook | Runs `clipsneko-reboot-required` after any listed essential system files have been updated.
lsb-release.hook | Runs `clipsneko-branding` script after package `lsb-release` has been updated.
os-release.hook | Runs `clipsneko-branding` scirpt after package `filesystem` has been updated.
update-initramfs | Helper script for autodetecting and using installed initramfs generator
