# Surface Pro 7 - macOS - OpenCore
---
OpenCore configuration for support macOS on Surface Pro 7


### Surface Specs
- Intel® Core™ i5-1035G4 Quad-Core
- 8 GB LPDDR4x RAM
- Intel® Iris™ Plus
- SSD 256 GB


### Status
|  Status             |         Feature                 |            Note                      |
|---------------------|---------------------------------|--------------------------------------|
|  :white_check_mark: |  Graphic Acceleration          |  QE/CI works |
|  :white_check_mark: |  Wifi & Bluetooth              |  With [OpenIntelWireless](https://github.com/OpenIntelWireless/itlwm) |
|  :white_check_mark: |  Type Cover  (keyboard/mouse)  |  With RHUB and [BigSurface](https://github.com/Xiashangning/BigSurface)|                             
|  :white_check_mark: |  Audio                         |  With AppleALC   |
|  :white_check_mark: |  Battery Status          |  With [BigSurface](https://github.com/Xiashangning/BigSurface)                 | 
|                     |                                |                   |
|  :heavy_exclamation_mark: |  Camera Front and Rear        |                   | 


### Install Notes
- For a better Wifi experience, use **itlwm** instead of **AirportItlwm** with [HeliPort](https://github.com/OpenIntelWireless/HeliPort) (Simple enable/disable them in `config.plist`)

### Secure Boot
If you want to boot without the anoing red bar with the lock icon you can try [this workaround](https://github.com/badstorm/surface-pro-7-opencore/blob/master/SecureBoot.With.Grub.md). *Thanks to @Xiashangning* 
