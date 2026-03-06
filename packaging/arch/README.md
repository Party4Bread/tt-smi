# Arch Linux Packaging

This repository includes an Arch Linux PKGBUILD at packaging/arch/PKGBUILD.

Build locally:

```bash
cd packaging/arch
makepkg --syncdeps --cleanbuild --clean --noconfirm
```

The package uses the checked-out repository as the source tree so CI validates the exact commit under test.
