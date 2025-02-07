# Thinkpad P50 Hackintosh
My EFI configuration for installing MacOS on the Thinkpad P50.
![desktop_screenshot](https://raw.githubusercontent.com/TwilightHacker/P50-hackintosh/dc3bde7dcf1461c139cf28f01a0bf7a2e848db6c/screenshot.png)

### Compatability
I have fully tested this configuration and confirms it working for MacOS Sonoma 14.7.3. It should also work for MacOS Ventura and Monterey as well. On all versions of MacOS Sonoma, the pc reboots twice before fully booting on the third attempt. For wifi, be sure to download the correct Airportlwm kext for the version you are trying to install.

### My Hardware
- CPU: Intel Xeon E3-1505M 2.8GHz Quad Core - Eight Threads
- GPU:
  * Intel HD P530
  * Nvidia Quadro M200M
    * Will never work (Is disabled)
- RAM: 16GB 2133MHz DDR4
- Storage:
  * 1TB Timetec M.2 SSD
    * MacOS
  * 1TB Timetec M.2 SSD
    * Windows 
- Wifi: Intel Dual Band Wireless-AC 8260
- Ethernet: Intel I219
- Display: 15.6" 1920x1080
- Audio: ALC298
- Thunderbolt 3

### What's Working
- Wifi/Bluetooth
- Audio
- Camera
- USB Ports
- HDMI
- GPU Acceleration (IGPU only)
- Trackpad (All gestures)
- Trackpoint
- Battery Reading
- iMessage/FaceTime/AirDrop/iCloud

### What's Not Working
- Sleep (Drains power when lid is closed)
- Thunderbolt 3
- ExpressCard
- SD Card Reader

### Currently Fixing
- [ ] Power Management
- [ ] Sleep
- [ ] SD Card Reader
