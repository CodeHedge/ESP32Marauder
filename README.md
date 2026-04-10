<!---[![License: MIT](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/CodeHedge/ESP32Marauder/blob/master/LICENSE)--->
<!---[![Gitter](https://badges.gitter.im/CodeHedge/ESP32Marauder.png)](https://gitter.im/CodeHedge/ESP32Marauder)--->
<!---[![Build Status](https://travis-ci.com/CodeHedge/ESP32Marauder.svg?branch=master)](https://travis-ci.com/CodeHedge/ESP32Marauder)--->
<!---Shields/Badges https://shields.io/--->

## About This Fork

This repository is a fork of the ESP32 Marauder firmware with modified capabilities specifically for CYD (Cheap Yellow Display) builds.

### Primary Modifications:

- **Battery Monitoring Support**: Integrated support for the [Adafruit MAX17048 Battery Fuel Gauge](https://www.adafruit.com/product/5580) connected to port CN1, providing real-time battery percentage display in the top-right corner of the screen.

- **GPS Port Relocation**: To accommodate the battery gauge, GPS functionality has been moved to the bottom port (P5).

- **Removed Marauder CLI**: CLI support has been dropped due to limited IO availability. The philosophy behind this decision is that devices with screens should leverage their display capabilities rather than rely on CLI interfaces. For CLI needs, an ESP32 Dev board would be more appropriate.

### Recommended Hardware

The [ESP32 Marauder Battery Mod Kit](https://biscuitshop.us/products/esp32-marauder-battery-mod-kit) is the primary board recommended for this fork, providing an integrated solution with all necessary components.

Alternatively, you can achieve the same functionality using the Adafruit MAX17048 board and a compatible GPS module with your existing CYD hardware.

## Getting Started

### Web Flasher
Flash your device directly from the browser using the web flasher: [https://codehedge.github.io/Adafruit_WebSerial_ESPTool/](https://codehedge.github.io/Adafruit_WebSerial_ESPTool/)

### Downloads
Download the [latest release](https://github.com/CodeHedge/ESP32Marauder/releases/latest) of the firmware.

### Documentation
Check out the project [wiki](https://github.com/justcallmekoko/ESP32Marauder/wiki) for a full overview of the ESP32 Marauder features and capabilities.
