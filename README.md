# My Custom Cantor Pro LP Wireless Keyboard

!(images/my-keyboard.jpg)
*(You can add a picture of your completed keyboard here)*

This repository contains all the files and configuration for my personal build of the **Cantor Pro LP**, a 40% low-profile, hotswap, split ergonomic keyboard. This build is fully wireless, using Nice!Nano controllers running the ZMK firmware.

## Table of Contents

- [Hardware Components](#hardware-components)
- [Firmware (ZMK)](#firmware-zmk)
- [3D Printed Case](#3d-printed-case)
- [Build Notes](#build-notes)
- [Acknowledgements](#acknowledgements)

---

## Hardware Components

| Component | Item | Notes |
| :--- | :--- | :--- |
| **Keyboard Kit** | PCBs ordered from JLCPCB but can be sorced from 42. Keebs: [Cantor Pro LP Kit](https://42keebs.eu/shop/kits/pro-micro-based/cantor-pro-lp-40-low-profile-hotswap-split-ergo-kit/) |
| **Controllers** | 2x Nice!Nano v2 (or alternative) | For wireless connectivity via Bluetooth. |
| **Batteries** | 2x 102050 LiPo (1000mAh) | One for each half. Fits perfectly with the custom case. |
| **Switches** | 42x Kailh Choc V1 `[Your Switch Type]` | in my case: Sunset, waiting for sunrise |
| **Keycaps** | 42x `[Your Keycap Set]` | e.g., MBK Blank Choc Keycaps. |
| **Case** | Custom 3D Printed Case & Cover | Files are located in the `/case` directory. |

---

## Firmware (ZMK)

This keyboard runs on the [ZMK Firmware](https://zmk.dev/docs), which is designed for wireless keyboards.

### My Configuration

* **ZMK Config:** The main configuration files are located in the `/confighttps://nickcoutsos.github.io/keymap-editor/` directory.

### Configure, Build & Flash
* Configuration: Done using awesome [Keymap Editor](https://nickcoutsos.github.io/keymap-editor/)
* Build: standard Github Actions
* Flash: To Flash consult Microcontroller Documentation

---

## 3D Printed Case

This build uses a custom-designed 3D printed case and a friction fit travel cover to protect the keys.

* **Files Location:** `/case`

### Recommended Print Settings

* **Material:** Any, preferabbly in ABS/ASA/PETG due to better heat resistance
* **Outer Walls:** minimum of 3
* **Layer Height:** 0.2mm
* **Infill:** 15-20%
* **Supports:** Not required

---


## Build Notes

* **Fully Wireless:** This build is fully wireless and does **not** use a TRRS cable. The two halves communicate via Bluetooth. The TRRS jacks on the PCB are not installed.
* **Battery Placement:** The batteries are not placed underneath the controllers. They are placed under in the Case. Due to tight tolerances, trim the PCB pins flush

---

## Acknowledgements

* **Cantor Keyboard:** Diego Palacios
* **Cantor Pro LP Kit:** [42. Keebs](https://42keebs.eu/)
* **ZMK Firmware:** The ZMK contributors.
