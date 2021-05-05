#  Redmibook14EE-hackintosh

Tested on redmibook 14 EE i5-10210u

***Make Sure to Change SMBIOS from config.plist***

## Contents

- [[SUCCESS] Xiaomi-Notebook14-Hackintosh](#success-xiaomi-notebook14-hackintosh)
  - [Contents](#contents)
  - [Configuration](#configuration)
  - [Current Status](#current-status)
  - [Credits](#credits)

## Configuration

| Specifications      | Detail                                              |
| ------------------- | --------------------------------------------------- |
| Computer model      | Redmibook 14 Enchanted Edition (MX250)              |
| Processor           | Intel Core i5-10210U/i7 Processor                   |
| Memory              | 8GB/16GB Samsung DDR4 2400MHz                       |
| Hard Disk           | Samsung NVMe SSD Controller                         |
| Integrated Graphics | Intel UHD Graphics 630                              |
| Monitor             | BOE NV156FHM-N61 FHD 1920x1080 (15.6 inch)          |
| Sound Card          | Realtek ALC256                                      |
| Wireless Card       | Intel Wireless 9462                                 |
| Touchpad            | I2C ELAN2304                                        |

## Current Status
> ### OpenCore 0.6.7 
 
- WIFI/Bluetooth Works 
- Audio Works
- Headphone Mic Works **Refer in improvement section**
- **Internal Mic Not Working**
- Power Management works (Battery last for about 5-6 hours)
- Touchpad Gestures Works
- HW acceleration enabled
- **Discrete graphic card** is not supported


## Credits
- **Special Thanks to [daliansky](https://github.com/daliansky) for providing [XiaoMi-Pro-Hackintosh](https://github.com/daliansky/XiaoMi-Pro-Hackintosh)**.
- Thanks to [Acidanthera](https://github.com/acidanthera) for providing [AppleALC](https://github.com/acidanthera/AppleALC), [AppleSupportPkg](https://github.com/acidanthera/AppleSupportPkg), [HibernationFixup](https://github.com/acidanthera/HibernationFixup), [Lilu](https://github.com/acidanthera/Lilu), [NVMeFix](https://github.com/acidanthera/NVMeFix), [OcBinaryData](https://github.com/acidanthera/OcBinaryData), [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg), [VirtualSMC](https://github.com/acidanthera/VirtualSMC), [VoodooInput](https://github.com/acidanthera/VoodooInput), [VoodooPS2](https://github.com/acidanthera/VoodooPS2), and [WhateverGreen](https://github.com/acidanthera/WhateverGreen).
- Thanks to [apianti](https://sourceforge.net/u/apianti), [blackosx](https://sourceforge.net/u/blackosx), [blusseau](https://sourceforge.net/u/blusseau), [dmazar](https://sourceforge.net/u/dmazar), and [slice2009](https://sourceforge.net/u/slice2009) for providing [Clover](https://github.com/CloverHackyColor/CloverBootloader).
- Thanks to [daliansky](https://github.com/daliansky) for providing [OC-little](https://github.com/daliansky/OC-little).
- Thanks to [hieplpvip](https://github.com/hieplpvip) and [syscl](https://github.com/syscl) for providing sample of DSDT patches.
- Thanks to [OpenIntelWireless](https://github.com/OpenIntelWireless) for providing [IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware).
- Thanks to [RehabMan](https://github.com/RehabMan) for providing [EAPD-Codec-Commander](https://github.com/RehabMan/EAPD-Codec-Commander), [EFICheckDisabler](https://github.com/RehabMan/hack-tools/tree/master/kexts/EFICheckDisabler.kext), [OS-X-Clover-Laptop-Config](https://github.com/RehabMan/OS-X-Clover-Laptop-Config), [OS-X-Null-Ethernet](https://github.com/RehabMan/OS-X-Null-Ethernet), and [SATA-unsupported](https://github.com/RehabMan/hack-tools/tree/master/kexts/SATA-unsupported.kext).
- Thanks to [VoodooI2C](https://github.com/VoodooI2C) for providing [VoodooI2C](https://github.com/VoodooI2C/VoodooI2C).
- Thanks to [One-Key-HiDPI](https://github.com/xzhih/one-key-hidpi)
- Thanks to [uttusharma](https://github.com/uttusharma) for providing [Xiaomi-Notebook14-Hackintosh](https://github.com/uttusharma/Xiaomi-Notebook14-Hackintosh)
