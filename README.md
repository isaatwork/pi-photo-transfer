# pi-photo-transfer
# Pi Photo Transfer

## Project Overview
A Raspberry Pi 5 based system that copies photo data from an SD card to a 
USB mobile SSD — fully battery powered. The Pi manages and supervises the 
data transfer with maximum speed and minimum power consumption.
A touch display GUI allows the user to initiate transfers and monitor progress.

**Supervisor:** Prof. Dr. Holger Glasmachers  
**Developer:** Isa  
**Started:** March 2026

---

## Hardware
- Raspberry Pi 5
- High speed SD card in SD-USB adapter
- USB mobile SSD (connected via USB to Pi)
- Touch display (connected to Pi)

---

## Goals
- Detect connected SD card and USB SSD automatically
- GUI for initiating file transfer
- Transfer photo data from SD to SSD
- Start with low speed, then optimize to maximum transfer speed
- Minimize electrical power consumption
- Fully battery powered system

---

## Tech Stack
- Language: Python
- GUI: TBD (PyQt6 or tkinter)
- Version control: Git + GitHub
- Development environment: Raspberry Pi 5 via VNC Viewer

---

## Roadmap
| Phase | Description | Status |
|-------|-------------|--------|
| 0 | Setup Pi 5, flash OS, connect via VNC | ✅ Done |
| 1 | Git & GitHub setup | ✅ Done |
| 2 | Hardware detection (SD card + SSD) | 🔲 Next |
| 3 | Low speed file transfer working | 🔲 Pending |
| 4 | Touch GUI development | 🔲 Pending |
| 5 | Speed & power optimization | 🔲 Pending |
| 6 | Documentation & Projektarbeit report | 🔲 Pending |

---

## Setup Log

### Pi Setup
- Downloaded and installed Raspberry Pi Imager on laptop
- Flashed Raspberry Pi OS onto SD card using Pi Imager
- Booted Pi 5 with the flashed SD card
- Enabled VNC on the Pi
- Installed VNC Viewer on laptop
- Connected to Pi remotely from laptop via VNC Viewer

### Git & GitHub Setup (March 2026)
- Installed Git on Raspberry Pi
- Configured Git identity (username and email)
- Created GitHub account and repository: pi-photo-transfer
- Generated SSH key on Pi (ed25519)
- Added SSH public key to GitHub account
- Tested SSH connection successfully
- Cloned repository onto Pi
- Ready to start coding

---

## How to Run
*(will be updated as development progresses)*

---

## Progress Log
*(updated regularly)*
- **February 2026** — Project started. Pi setup complete. Git and GitHub connected.
