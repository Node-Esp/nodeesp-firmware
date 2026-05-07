<div align="center">

# NodeESP Firmware

Official firmware distribution repository for **NodeESP** devices.

Build, publish, and deliver firmware updates for ESP-based IoT hardware through the NodeESP platform.

[![Website](https://img.shields.io/badge/Website-nodeesp.com-blue?style=for-the-badge&logo=google-chrome&logoColor=white)](https://nodeesp.com)
[![Platform](https://img.shields.io/badge/Platform-NodeESP-111827?style=for-the-badge)](https://nodeesp.com)
[![Device](https://img.shields.io/badge/Device-ESP32--C6-green?style=for-the-badge&logo=espressif&logoColor=white)](https://www.espressif.com/)
[![Firmware](https://img.shields.io/badge/Firmware-OTA%20Ready-orange?style=for-the-badge)](#firmware-updates)

<br />

[![GitHub repo size](https://img.shields.io/github/repo-size/Node-Esp/nodeesp-firmware?style=flat-square)](https://github.com/Node-Esp/nodeesp-firmware)
[![GitHub last commit](https://img.shields.io/github/last-commit/Node-Esp/nodeesp-firmware?style=flat-square)](https://github.com/Node-Esp/nodeesp-firmware/commits/main)
[![GitHub commit activity](https://img.shields.io/github/commit-activity/m/Node-Esp/nodeesp-firmware?style=flat-square)](https://github.com/Node-Esp/nodeesp-firmware/commits/main)
[![GitHub issues](https://img.shields.io/github/issues/Node-Esp/nodeesp-firmware?style=flat-square)](https://github.com/Node-Esp/nodeesp-firmware/issues)
[![GitHub stars](https://img.shields.io/github/stars/Node-Esp/nodeesp-firmware?style=flat-square)](https://github.com/Node-Esp/nodeesp-firmware/stargazers)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=flat-square)](#license)

</div>

---

## Overview

**NodeESP Firmware** is the official firmware release repository for NodeESP-compatible ESP devices.

This repository stores compiled firmware binaries, versioned firmware folders, and the firmware manifest used by the NodeESP platform to check for available updates.

NodeESP is designed to make ESP-based device management simple, visual, and scalable through a web-based interface.

The firmware hosted here supports features such as:

- OTA firmware updates
- ESP device version tracking
- Cloud-connected device management
- Local HTTP device discovery
- Visual node-based device configuration
- Virtual device testing before hardware deployment
- Future support for multiple ESP-based boards

---

## About NodeESP

**NodeESP** is an IoT platform built for managing ESP devices through a clean and modern web interface.

With NodeESP, users can connect supported ESP devices, configure behavior visually, deploy logic, and manage firmware updates from one place.

Website: [nodeesp.com](https://nodeesp.com)

---

## Repository Purpose

This repository is primarily used for **firmware distribution**, not firmware source development.

It contains:

| File / Folder | Purpose |
|---|---|
| `firmware-manifest.json` | Tells the NodeESP platform which firmware versions are available |
| `esp32-c6/` | Firmware binaries for ESP32-C6 devices |
| `firmware.bin` | Compiled firmware binary used for OTA updates |
| `README.md` | Repository documentation |

---

## Repository Structure

```txt
nodeesp-firmware/
├── esp32-c6/
│   └── v1.0.0/
│       └── firmware.bin
├── firmware-manifest.json
└── README.md
