<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 3.95″ TFT 480×480 (ST7102 · MIPI)</h1>

<p align="center"><b>Square TFT module · MIPI · ST7102 · In-Cell (ST7123)</b></p>

<p align="center"><a href="./README.md">简体中文</a> | English · <a href="../../README_EN.md">Family index</a></p>

<p align="center">
  <img alt="Size: 3.95 inch" src="https://img.shields.io/badge/Size-3.95%22-3498DB?style=flat-square" />
  <img alt="Resolution: 480x480" src="https://img.shields.io/badge/Resolution-480%C3%97480-8E44AD?style=flat-square" />
  <img alt="Interface: MIPI" src="https://img.shields.io/badge/Interface-MIPI-27AE60?style=flat-square" />
  <img alt="Driver: ST7102" src="https://img.shields.io/badge/Driver-ST7102-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 3.95 inch 480x480 TFT MIPI module (ST7102)" src="./images/product.png" width="640" /></p>

## Contents

- [Overview](#overview)
- [Specifications](#specifications)
- [Sample projects](#sample-projects)
- [Repository layout](#repository-layout)
- [Resources](#resources)
- [Buy](#buy)
- [Support](#support)

---

## Overview

OSPTEK **3.95″ 480×480 TFT** is a **MIPI** color display module driven by **ST7102**, with **In-Cell** capacitive touch (**ST7123**). Suited to square HMI, instruments, and mid-size interactive panels.

Spec ID (repository name): `tft-3.95-480x480-mipi-st7102`

Current module version: **YDP395BT008-V1**. Electrical and mechanical details follow [`docs/YDP395BT008-V1.pdf`](./docs/YDP395BT008-V1.pdf).

## Specifications

| Item | Spec |
| ---- | ---- |
| Size | 3.95 inch |
| Type | TFT / IPS (color) |
| Resolution | 480×480 |
| Interface | MIPI |
| Driver IC | ST7102 |
| Touch driver | ST7123 (In-Cell) |

> Full outline, FPC definition, power, and timing follow the product datasheet / driver IC datasheet.

## Sample projects

| Description | Path |
| ---- | ---- |
| ESP32-P4 · ST7102 MIPI + ST7123 touch bringup | [`examples/esp32p4-tft-3.95-480x480-mipi-st7102-bringup/`](./examples/esp32p4-tft-3.95-480x480-mipi-st7102-bringup/) |
| Raspberry Pi 5 · ST7102 480×480 panel / DT overlay (display only) | [`examples/rpi5-panel-st7102-480x480/`](./examples/rpi5-panel-st7102-480x480/) |
| Raspberry Pi 5 · ST7102 display + ST7123 touch / DT overlay | [`examples/rpi5-panel-st7102-st7123-480x480/`](./examples/rpi5-panel-st7102-st7123-480x480/) |
| Raspberry Pi 5 · ST7102 + ST7123 · LVGL (DRM + EVDEV) | [`examples/rpi5-lvgl-st7102-st7123-480x480/`](./examples/rpi5-lvgl-st7102-st7123-480x480/) |

## Repository layout

```text
tft-3.95-480x480-mipi-st7102/  # repo root (nav: ../../README_EN.md)
└── versions/
    └── YDP395BT008-V1/        # full materials for this part number
        ├── README.md
        ├── README_EN.md
        ├── images/
        ├── docs/
        └── examples/
```

## Resources

### Product files

| Resource | Link |
| ---- | ---- |
| Product datasheet (YDP395BT008-V1) | [`docs/YDP395BT008-V1.pdf`](./docs/YDP395BT008-V1.pdf) |
| Driver IC datasheet (ST7102) | [`docs/ST7102_Datasheet_V0.22.pdf`](./docs/ST7102_Datasheet_V0.22.pdf) |

### Samples

- [ESP32-P4 ST7102 MIPI + ST7123 bringup](./examples/esp32p4-tft-3.95-480x480-mipi-st7102-bringup/)
- [Raspberry Pi 5 ST7102 panel (display only)](./examples/rpi5-panel-st7102-480x480/)
- [Raspberry Pi 5 ST7102 display + ST7123 touch](./examples/rpi5-panel-st7102-st7123-480x480/)
- [Raspberry Pi 5 ST7102 + ST7123 · LVGL](./examples/rpi5-lvgl-st7102-st7123-480x480/)

## Buy

<p align="center">
  <a href="https://www.aliexpress.com/store/1105701619"><img alt="AliExpress store" src="https://img.shields.io/badge/AliExpress-Official_Store-FF6A00?style=for-the-badge" /></a>
  &nbsp;&nbsp;
  <a href="https://shop110742373.taobao.com/"><img alt="Taobao store" src="https://img.shields.io/badge/Taobao-Official_Store-FF6A00?style=for-the-badge" /></a>
</p>

**Overseas (AliExpress)**

- Store: [OSPTEK Official Store](https://www.aliexpress.com/store/1105701619)

**China (Taobao)**

- Store: [鱼鹰光电工厂店](https://shop110742373.taobao.com/)

## Support

- Technical support / product inquiry: <luyu@osptek.com>
- QQ group (China): **985881096**
- Website: <https://osptek.com/>
- Feel free to open an Issue in this repository if you have any questions

---

<p align="center"><sub>© 2026 OSPTEK · Materials in this repository are licensed under CC BY 4.0</sub></p>
