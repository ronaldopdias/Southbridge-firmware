# Southbridge firmware

Firmware and tools used by Southbridge, published so the app can check for updates.

## POST adapter firmware

Each release tagged `vX.Y.Z` holds `southbridge-post-adapter-vX.Y.Z.zip` with one file per adapter board:

| Board | File |
|---|---|
| Raspberry Pi Pico | `southbridge_post_adapter_pico.uf2` |
| Raspberry Pi Pico 2 | `southbridge_post_adapter_pico2.uf2` |
| ESP32 | `southbridge_post_adapter_esp32.bin` |
| ESP32-S3 | `southbridge_post_adapter_esp32s3.bin` |

Licence: see [LICENSE-adapter-firmware.txt](LICENSE-adapter-firmware.txt).

## ESP32 flashing tool

The release tagged `esptool-v5.6.0` holds the unmodified Windows build of esptool v5.6.0 and its complete source
code. esptool is free software under the GNU General Public License, version 2 or later; see
[LICENSE-esptool.txt](LICENSE-esptool.txt).
