## Hardware
See my [Hardware List](HARDWARE.md)

## MacOS
10.15.3 (19D76)

## What's Working

- [x] Display
    - [x] Intel UHD Graphics 630 (DP)
    ![gup](img/gpu.png)
- [x] Ethernet
- [x] Sleep/Wake
![sleep/Wake](img/sleep_wake.png)
- [x] Bluetooth & Wi-Fi
    - [x] Airdrop
    - [x] Handoff & Continuity
- [x] USB ports
    - [x] iPhone fast charging
    ![fast_charging](img/usb_charging.png)
    - [x] custom usb ports
    ![usb](img/usb.png)
- [x] CPU Frequency
![cpu](img/cpu.png)

Others not tested is what I do not used.

## BIOS setting
 - DVMT Pre-Allcated -> `128M`
 - fast boot -> `disable`

## Software
- [Clover Installer](https://github.com/Dids/clover-builder/releases)
- [Clover Configurator](https://mackie100projects.altervista.org/download-clover-configurator/)
- [FakeSMC.kext](https://bitbucket.org/RehabMan/os-x-fakesmc-kozlek/downloads/)
- [Lilu.kext](https://github.com/acidanthera/Lilu/releases)
- [WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen/releases)
- [USBInjectAll.kext](https://bitbucket.org/RehabMan/os-x-usb-inject-all/downloads/)
  - [XHCI-unsupported.kext](https://github.com/RehabMan/OS-X-USB-Inject-All)
- [IntelMausiEthernet.kext](https://bitbucket.org/RehabMan/os-x-intel-network/downloads/)
- [AppleALC.kext](https://github.com/acidanthera/AppleALC/releases)

## Tool
- [USBmap](https://github.com/corpnewt/USBMap)

To verify whether you have correctly setup your EC device, grab CorpNewt's [USBmap tool](https://github.com/corpnewt/USBMap) and choose `Validate USB Power Settings`. This should return the following:
```
Checking EC
 - EC is properly setup
Checking USBX requirements
 - SMBIOS not found in IOUSBHostFamily.kext - checking for USBX
 --> USBX device found: USBX@0

EC Setup Properly:   True
USBX Setup Properly: True
```
- [iMessageDebug](https://mac.softpedia.com/get/System-Utilities/iMessageDebug.shtml)
- [Hackintool](https://www.tonymacx86.com/threads/release-hackintool-v2-8-6.254559/)
- [Intel Power Gadget](https://software.intel.com/en-us/articles/intel-power-gadget)
- [VideoProc](https://www.videoproc.com/)

## PS
EFI-INSTALL is used in my first installation, and it given from the author of [this article](http://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1816236)

If you have an optimization plan, it would be nice if you let me know so I can improve the EFI. 
