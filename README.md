# Pi Photo Transfer

## Project Overview
A Raspberry Pi 5 based system that copies photo data from an SD card to a
USB mobile SSD — fully battery powered. The Pi manages and supervises the
data transfer with maximum speed and minimum power consumption.
A touch display with a file manager style GUI (like Windows Explorer) allows
the user to browse and initiate transfers using finger touch.

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
- Understand Pi 5 USB controller and optimize communication speed
- Detect connected SD card and USB SSD automatically
- Copy photo data from SD card to SSD at maximum speed
- Minimize electrical power consumption
- Touch-friendly file manager GUI (Windows Explorer style)
- Fully battery powered system

---

## Tech Stack
- Language: Python
- GUI: TBD (existing touch file manager or PyQt6)
- Version control: Git + GitHub
- Development environment: Raspberry Pi 5 via VNC Viewer

---

## Roadmap
| Phase | Description | Status |
|-------|-------------|--------|
| 0 | Setup Pi 5, flash OS, connect via VNC, Git & GitHub | ✅ Done |
| 1 | Research: USB controller, OS comparison, touch GUI options | 🔄 In Progress |
| 2 | Hardware detection (SD card + SSD) | 🔲 Pending |
| 3 | Low speed file transfer working | 🔲 Pending |
| 4 | Touch GUI file manager | 🔲 Pending |
| 5 | Maximum speed & power optimization | 🔲 Pending |
| 6 | Documentation & Projektarbeit report | 🔲 Pending |

---

## Research Notes

### Pi 5 USB Controller
*(to be filled during Phase 1)*

### OS Comparison for USB Performance
*(to be filled during Phase 1)*

### Touch File Manager Options
*(to be filled during Phase 1)*

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

---

## Progress Log
- **March 2026** — Project started. Pi setup complete. Git and GitHub connected.
- **March 2026** — README updated. Roadmap revised based on professor feedback.
- **March 2026** — Phase 1 research started: USB controller, OS comparison, touch GUI.

---

## How to Run
*(will be updated as development progresses)*
