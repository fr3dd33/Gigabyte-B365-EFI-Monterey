![GitHub release](https://img.shields.io/github/v/release/fr3dd33/Gigabyte-B365-EFI-Monterey?style=flat-square)
![GitHub release date](https://img.shields.io/github/release-date/fr3dd33/Gigabyte-B365-EFI-Monterey?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/fr3dd33/Gigabyte-B365-EFI-Monterey?style=flat-square)
![GitHub download latest](https://img.shields.io/github/downloads/fr3dd33/Gigabyte-B365-EFI-Monterey/latest/total?style=flat-square)
![GitHub download total](https://img.shields.io/github/downloads/fr3dd33/Gigabyte-B365-EFI-Monterey/total?style=flat-square)  
![GitHub stars](https://img.shields.io/github/stars/fr3dd33/Gigabyte-B365-EFI-Monterey?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/fr3dd33/Gigabyte-B365-EFI-Monterey?style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/fr3dd33/Gigabyte-B365-EFI-Monterey?style=flat-square)
![GitHub issues closed](https://img.shields.io/github/issues-closed/fr3dd33/Gigabyte-B365-EFI-Monterey?style=flat-square)

# Getting Started and Documentation
https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#starting-point

## Hardware 
+ Motherboard: Gigabyte B365M H
+ CPU: Intel Core i7-9700
+ GPU: UHD 630
+ RAM: Lexar 32GB DDR4 (2333 Mhz)
+ SSD: Samsung QVO 870 1TB

## BIOS settings:
+ BIOS:
  - Fast Boot -> Disabled
  - CSM Support -> Disabled
  - Secure Boot -> Disabled  

+ Peripherals:
   - Initial Display Output -> IGFX
   - Above 4G Decoding -> Enabled
   - Intel Platform Trust Technology (PTT) -> Disabled  
   - SW Guard Extensions (SGX) -> Disabled  
   - Super IO Configuration -> Serial Port -> Disabled  
   - Super IO Configuration -> Parallel Port -> Disabled
   - USB Configuration -> Legacy USB support -> Disabled  
   - USB Configuration -> XHCI Hand-of -> Enabled  
   - Network Stack Configuration -> Network Stack -> Disabled  
   - SATA Mode Selection -> AHCI  

+ Chipset:
    - VT-d -> Disabled  
    - Internal Graphics -> Enabled
    - DVMT Pre-Allocation -> 64M  
    - DVMT Total Gfx Mem -> MAX

## Kexts
- [Lilu.kext 1.5.9](https://github.com/acidanthera/Lilu)
- [WhateverGreen.kext 1.5.6](https://github.com/acidanthera/WhateverGreen)
- [SMCProcessor.kext 1.2.8](https://github.com/acidanthera/VirtualSMC)
- [SMCSuperIO.kext 1.2.8](https://github.com/acidanthera/VirtualSMC)
- [VirtualSMC.kext 1.2.8](https://github.com/acidanthera/VirtualSMC)
- [AppleALC.kext 1.6.8](https://github.com/acidanthera/AppleALC)
- [RealtekRTL8111Ethernet](https://github.com/Mieze/RTL8111_driver_for_OS_X)

## Tools
- [Hackintool](https://github.com/headkaze/Hackintool)
- [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) Generate SMBIOS.
- [MountEFI](https://github.com/corpnewt/MountEFI) Mount EFI partition.
- [USBMAP](https://github.com/corpnewt/USBMap) Manually map USB Ports.
- [ProperTree](https://github.com/corpnewt/ProperTree) Plist editor.