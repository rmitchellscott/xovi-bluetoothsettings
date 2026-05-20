# reMarkable Bluetooth Settings
[![rmpp](https://img.shields.io/badge/rMPP-supported-green)](https://remarkable.com/store/overview/remarkable-paper-pro)
[![rmppmove](https://img.shields.io/badge/rMPPMove-supported-green)](https://remarkable.com/products/remarkable-paper/pro-move)
[![vellum](https://img.shields.io/badge/vellum-bluetooth--settings-purple)](https://vellum.delivery/#/package/bluetooth-settings/)


Adds a Bluetooth settings page to xochitl, allowing pairing and management of Bluetooth keyboards directly from the reMarkable UI.

<img src="assets/bluetoothSettings-screenshot.png" height="400"/>

## Installation

Installation via the [Vellum package manager](https://github.com/vellum-dev/vellum) is recommended. Dependencies are handled automatically.

### Manual

Requires [xovi](https://github.com/asivery/rmpp-xovi-extensions), qt-resource-rebuilder, and qt-command-executor.

Download `bluetoothSettings.qmd` from the [latest release](https://github.com/rmitchellscott/xovi-bluetoothsettings/releases/latest).

Copy to `/home/root/xovi/exthome/qt-resource-rebuilder/` and restart xovi.

The `icons/bluetooth.rcc` file must also be placed alongside the QMD.
