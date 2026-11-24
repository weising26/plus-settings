# Plus+ and GO Plus settings pages

Web pages that connect over Web Bluetooth to a Pokémon GO Plus emulator and
change its settings. Open them in **Chrome on Android**.

| Page | Device | Settings |
|---|---|---|
| [index.html](index.html) | nRF52 Plus+ emulator (XIAO nRF52840) | auto-catch, auto-spin, Pokémon Sleep data, light sleep delay, pairing reset, status |
| [pgp.html](pgp.html) | pgpemu GO Plus emulator (XIAO ESP32-S3) | auto-catch, auto-spin, phones at once, LED, power bank ping, log level, secrets slot, button, restart, status |

Each page needs firmware that includes its settings service. For the Plus+,
disconnect the device from Pokémon GO first. The GO Plus page can connect while
phones are playing, as long as the device is still advertising.

This repository contains only the pages. It holds no device keys, flash images
or BLE addresses.
