# Hackintosh OpenCore

- EFI folder for Acer A515-52G-577T
- OpenCore 0.8.7
- MacOS Monterey (12.6.1) and Ventura (13.0.1)

## Before Stating

- You must generate your own SMBIOS and update it on the config.plist before boot
- If the macOS Ventura won't install you might try installing Monterey instead and after succeed update it to Ventura on the MacOS Settings

## Features

- [x] Ethernet
- [x] Sound
- [x] * HDMI
- [x] * Wifi / Bluetooth - With BCM94352Z
- [x] Airdrop / Handsoff
- [x] USB Mapping
- [x] TrackPad Gestures
- [x] Power Management
- [ ] GPU MX130 - Unsupported

## BIOS

Firmware Version: v1.14

- Disable Secure Boot
- Disable Fast Boot
- Disable VT-d
- Enable VT-x
- Change Sata Mode to AHCI

## Issues

- HDMI audio might not work after reboot: try to shutdown and turn the PC back on
- HDMI display make not work after sleep: try to unplug the HDMI cable and plug it back on twice
- Bluetooth device is listed but not connecting: shutdown the PC and clear NVRam

## Credits

- [tucano3000](https://github.com/tucano3000/ACER-A515-52G-58LZ-HACKINTOSH-OPENCORE) - Initial work for A515-52G-58LZ
