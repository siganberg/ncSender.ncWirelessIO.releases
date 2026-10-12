# ncWirelessIO Firmware Releases

This repository hosts released firmware images for the ncWirelessIO (wireless I/O for ncSender). See the [Releases](https://github.com/siganberg/ncSender.ncWirelessIO.releases/releases) page.

Each release carries two assets:

- `firmware_ncwirelessio_vX.Y.Z.bin` — application image, used by the OTA update path (wireless or USB) in ncSender.
- `firmware_ncwirelessio_factory_vX.Y.Z.bin` — merged bootloader + partitions + boot_app0 + firmware, flashed at `0x0` to provision stock hardware.
