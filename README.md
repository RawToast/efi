# EFI

My personal OpenCore EFI configuration. Using [Opencore 0.5.9](https://github.com/acidanthera/OpenCorePkg)

Based on examples by [Technolli](https://www.technolli.com) and tweaked based on various examples on hackintosh forums. It seems the ITX X570 motherboards are very similar, so you might be able to just use these files with only serial number changes.

## Current System

* Ryzen 3600
* Gigabyte Aorus x570i Pro Wifi
* Gigabyte 5600XT Windforce
* Seagate FireCuda 520
* 32GB RAM!

## Whats working

I haven't tested everything yet... like sleep, etc.

- [x] Installs and boots
- [x] HDMI Sound
- [x] Ethernet
- [x] Apple Services
- [X] Bluetooth - fixed! Airpods, Magic Keyboard, Bluetooth networking, all work.
- [ ] Wifi (Expected, this chipset is not supported. Not a concern right now)

## BIOS Tweaks

* Set to optimised defaults
* Disable CSM

Note that these files have my serials removed, so you will have to update them. 
