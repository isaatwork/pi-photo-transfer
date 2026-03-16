# Phase 1 Research Notes

## 1. Pi 5 USB Controller

- Pi 5 uses a custom chip called RP1 to control all USB ports
- Has 2x USB 3.0 ports (blue, 5 Gbps) and 2x USB 2.0 ports (black, 480 Mbps)
- Always use USB 3.0 ports for SD card adapter and SSD
- RP1 removes the USB bottleneck that existed in older Pi models
- Data path: SD card > USB 3.0 > RP1 > Pi CPU > RP1 > USB 3.0 > SSD
- Transfer speed affected by: port choice, adapter quality, SSD quality, buffer size in code

## 2. OS Comparison for USB Performance

- Raspberry Pi OS 64-bit - best choice, native RP1 USB controller support
- Ubuntu 24.04 - good USB but heavier, more complex setup
- Raspberry Pi OS Lite - no desktop, not suitable for GUI project
- Windows IoT - poor USB support, not suitable

Decision: Stay with Raspberry Pi OS 64-bit
- Already installed on Pi
- Best USB 3.0 performance out of the box
- Best Python library support for this project
- No need to reflash or change OS

## 3. Touch File Manager Options

*(filling in progress)*
