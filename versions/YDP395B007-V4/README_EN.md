<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 3.95″ TFT 480×480 (ST7102 · MIPI)</h1>

<p align="center"><b>Square TFT module · MIPI · ST7102 · capacitive touch</b></p>

<p align="center"><a href="./README.md">简体中文</a> | English · <a href="../../README_EN.md">Family index</a></p>

<p align="center">
  <img alt="Size: 3.95 inch" src="https://img.shields.io/badge/Size-3.95%22-3498DB?style=flat-square" />
  <img alt="Resolution: 480x480" src="https://img.shields.io/badge/Resolution-480%C3%97480-8E44AD?style=flat-square" />
  <img alt="Interface: MIPI" src="https://img.shields.io/badge/Interface-MIPI-27AE60?style=flat-square" />
  <img alt="Driver: ST7102" src="https://img.shields.io/badge/Driver-ST7102-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 3.95″ 480×480 TFT MIPI module (ST7102) product image" src="./images/product.png" width="640" /></p>

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

OSPTEK **3.95″ 480×480 TFT** is a **MIPI** color display module driven by **ST7102**, with capacitive touch (**ST7123**). Suited to square HMI, instruments, and mid-size interactive panels.

Spec ID (repository name): `3.95-tft-480x480-mipi-st7102`

Current module version: **YDP395B007-V4**. Electrical and mechanical details follow [`docs/YDP395B007-V4.pdf`](./docs/YDP395B007-V4.pdf).

## Specifications

| Item | Spec |
| ---- | ---- |
| Size | 3.95 inch |
| Type | TFT / IPS (color) |
| Resolution | 480×480 |
| Interface | MIPI |
| Driver IC | ST7102 |
| Touch driver | ST7123 |

> Full outline, FPC definition, power, and timing follow the product datasheet / driver IC datasheet.

## Sample projects

| Description | Path |
| ---- | ---- |
| ESP32-P4 · ST7102 MIPI + esp-lvgl-port / LVGL9 | [`examples/esp32p4-idf5_st7102-mipi_esp-lvgl-port_lvgl9/`](./examples/esp32p4-idf5_st7102-mipi_esp-lvgl-port_lvgl9/) |
| ESP32-P4 · LVGL9 + TE | [`examples/with-te/esp32p4-idf5_st7102-mipi_lvgl9-common-demo/`](./examples/with-te/esp32p4-idf5_st7102-mipi_lvgl9-common-demo/) |
| ESP32-P4 · JPEG decode | [`examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode/`](./examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode/) |
| ESP32-P4 · JPEG decode + LVGL9 | [`examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_lvgl-v9/`](./examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_lvgl-v9/) |
| ESP32-P4 · JPEG decode + digital clock + LVGL9 | [`examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_digital-clock_lvgl-v9/`](./examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_digital-clock_lvgl-v9/) |
| ESP32-P4 · JPEG batch loop display | [`examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_batch-loop-display/`](./examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_batch-loop-display/) |
| ESP32-P4 · JPEG batch loop display + LVGL9 | [`examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_lvgl-v9_batch-loop-display/`](./examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_lvgl-v9_batch-loop-display/) |
| ESP32-P4 · MJPEG decode | [`examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode/`](./examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode/) |
| ESP32-P4 · MJPEG decode + LVGL9 | [`examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_lvgl-v9/`](./examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_lvgl-v9/) |
| ESP32-P4 · MJPEG batch loop display | [`examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_batch-loop-display/`](./examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_batch-loop-display/) |
| ESP32-P4 · MJPEG batch loop display + LVGL9 | [`examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_batch-loop-display_lvgl-v9/`](./examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_batch-loop-display_lvgl-v9/) |
| ESP32-P4 · MJPEG decode (dual-core) | [`examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_dual-core/`](./examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_dual-core/) |
| ESP32-P4 · MJPEG decode + LVGL9 (dual-core) | [`examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_lvgl-v9_dual-core/`](./examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_lvgl-v9_dual-core/) |
| Raspberry Pi 5 · ST7102 480×480 panel / DT overlay (display only) | [`examples/rpi5-panel-st7102-480x480/`](./examples/rpi5-panel-st7102-480x480/) |
| Raspberry Pi 5 · ST7102 display + ST7123 touch / DT overlay | [`examples/rpi5-panel-st7102-st7123-480x480/`](./examples/rpi5-panel-st7102-st7123-480x480/) |
| Raspberry Pi 5 · ST7102 + ST7123 · LVGL9 runner | [`examples/rpi5-lvgl-st7102-st7123-480x480/`](./examples/rpi5-lvgl-st7102-st7123-480x480/) |

## Repository layout

```text
3.95-tft-480x480-mipi-st7102/          # repo root (nav: ../../README_EN.md)
└── versions/
    └── YDP395B007-V4/                 # full materials for this part number
        ├── README.md
        ├── README_EN.md
        ├── images/                    # README assets
        ├── docs/                      # datasheets, init, etc.
        └── examples/                  # sample projects
```

## Resources

### Product files

| Resource | Link |
| ---- | ---- |
| Product datasheet (YDP395B007-V4) | [`docs/YDP395B007-V4.pdf`](./docs/YDP395B007-V4.pdf) |
| Adapter board (shared with BG006) | [`docs/3.95-ST7102-MIPI_转接板.pdf`](./docs/3.95-ST7102-MIPI_%E8%BD%AC%E6%8E%A5%E6%9D%BF.pdf) |
| Driver IC datasheet (ST7102) | [`docs/ST7102_Datasheet_V0.22.pdf`](./docs/ST7102_Datasheet_V0.22.pdf) |
| Init sequence (text) | [`docs/CODE.txt`](./docs/CODE.txt) |
| 3.95″ ST7102 MIPI board (V1.1) | [`docs/3.95 ST7102 MIPI屏幕V1.1.pdf`](./docs/3.95%20ST7102%20MIPI%E5%B1%8F%E5%B9%95V1.1.pdf) |

### Samples

- [ESP32-P4 ST7102 MIPI + LVGL9](./examples/esp32p4-idf5_st7102-mipi_esp-lvgl-port_lvgl9/)
- [ESP32-P4 LVGL9 + TE](./examples/with-te/esp32p4-idf5_st7102-mipi_lvgl9-common-demo/)
- [ESP32-P4 JPEG decode](./examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode/)
- [ESP32-P4 JPEG decode + LVGL9](./examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_lvgl-v9/)
- [ESP32-P4 JPEG decode + digital clock + LVGL9](./examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_digital-clock_lvgl-v9/)
- [ESP32-P4 JPEG batch loop display](./examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_batch-loop-display/)
- [ESP32-P4 JPEG batch loop display + LVGL9](./examples/jpg-decoder/p4-idf_st7102-mipi_jpeg-decode_lvgl-v9_batch-loop-display/)
- [ESP32-P4 MJPEG decode](./examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode/)
- [ESP32-P4 MJPEG decode + LVGL9](./examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_lvgl-v9/)
- [ESP32-P4 MJPEG batch loop display](./examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_batch-loop-display/)
- [ESP32-P4 MJPEG batch loop display + LVGL9](./examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_batch-loop-display_lvgl-v9/)
- [ESP32-P4 MJPEG decode (dual-core)](./examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_dual-core/)
- [ESP32-P4 MJPEG decode + LVGL9 (dual-core)](./examples/mjpeg/p4-idf_st7102-mipi_mjpeg-decode_lvgl-v9_dual-core/)
- [Raspberry Pi 5 ST7102 panel (display only)](./examples/rpi5-panel-st7102-480x480/)
- [Raspberry Pi 5 ST7102 display + ST7123 touch](./examples/rpi5-panel-st7102-st7123-480x480/)
- [Raspberry Pi 5 ST7102 + ST7123 · LVGL9](./examples/rpi5-lvgl-st7102-st7123-480x480/)

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
- QQ group: **985881096**
- Website: <https://osptek.com/>
- Feel free to open an Issue in this repository with any questions

---

<p align="center"><sub>© 2026 OSPTEK · Materials in this repository are licensed under CC BY 4.0</sub></p>
