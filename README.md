# Third-party sources and notices

This repository publishes third-party licence notices and pinned upstream
source for helper components redistributed with the NETO Windows installer.

It is not the NETO application source. It does not apply one licence to
every file. Each upstream component keeps the licence text included with it.

This is a download of those materials. It is not a statement that every
redistribution obligation has been cleared.

## Download

Archive:

<https://github.com/YM0527140225/NETO-third-party-notices/releases/download/corresponding-source-2026-11-08/neto-third-party-corresponding-source-2026-11-08.tar.gz>

SHA-256 (`SHA256SUMS`):

```
021e99b1c841e07fa38f97aae011de471c6581c60cf38d5547ca2c3a6c2bcd41
```

[INVENTORY.json](INVENTORY.json) lists the 19 files inside the archive and the SHA-256 of each file.

## What is inside

- Upstream source archives, byte-identical to the public Git tags:
  - [libwdi 1.5.1](https://github.com/pbatard/libwdi/releases/tag/v1.5.1)
  - [libusb-win32 1.4.0.0](https://github.com/mcuee/libusb-win32/releases/tag/release_1.4.0.0)
  - [libusbK 3.1.0.0](https://github.com/mcuee/libusbk/releases/tag/V3.1.0.0)
- Licence notices for those components (LGPL, GPL, BSD, Apache-2.0, the Microsoft WDF 1.11 redistributable licence text, and the Google platform-tools NOTICE)
- Short provenance notes for the WinUSB helper

Not included: NETO application source, installer logic, helper binaries built for the installer, signing keys, tokens, and backups. Microsoft does not publish source for the WDF co-installers; only the redistributable licence text is included.

Internal paths were removed from NETO-written notes before publication. Upstream licence texts and the three source archives were not modified.
