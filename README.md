#  Redmibook14EE-hackintosh

Протестировано на redmibook 14 EE i5-10210u

***Чтобы работали сервисы Apple, нужно поменять SMBIOS в config.plist***

## Содержание

- [SUCCESS] Redmibook 14 EE]
  - [Содержание](#cодержание)
  - [Конфигурация](#конфигурация)
  - [Текущий статус](#текущий-статус)
  - [Credits](#credits)

## Конфигурация

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

## Текущий статус

| Components\OS     | BigSur |
| ----------------- | :----: |
| Touchpad/Gestures |   ✅    |
| Keyboard          |   ✅    |
| Audio             |   🟢    |
| Microphone        |   🟢    |
| Wifi              |   ✅    |
| Bluetooth         |   ✅    |
| Sleep/Wake        |   ✅    |
| Power Management  |   ✅    |
| Graphic Acc.      |   ✅    |
| Backlight         |   ✅    |
| Brightness Key    |   ✅    |
| Hibernation       |   🤷‍♂️    |

```md
✅  : Working out of the box

🟢  : Some additional steps required to make it work

🟡  : Working but not perfectly i.e buggy currently

❌  : Not working currently

🤷‍♂️ : Haven't tested properly yet
```

## Credits
- Огромное спасибо [uttusharma](https://github.com/uttusharma) за предоставление [Xiaomi-Notebook14-Hackintosh](https://github.com/uttusharma/Xiaomi-Notebook14-Hackintosh). Только благодаря ему, я смог завести osx на Redmibook 14 EE.

- **Special Thanks to [daliansky](https://github.com/daliansky) for providing [XiaoMi-Pro-Hackintosh](https://github.com/daliansky/XiaoMi-Pro-Hackintosh)**.
- Thanks to [Acidanthera](https://github.com/acidanthera) for providing [AppleALC](https://github.com/acidanthera/AppleALC), [AppleSupportPkg](https://github.com/acidanthera/AppleSupportPkg), [HibernationFixup](https://github.com/acidanthera/HibernationFixup), [Lilu](https://github.com/acidanthera/Lilu), [NVMeFix](https://github.com/acidanthera/NVMeFix), [OcBinaryData](https://github.com/acidanthera/OcBinaryData), [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg), [VirtualSMC](https://github.com/acidanthera/VirtualSMC), [VoodooInput](https://github.com/acidanthera/VoodooInput), [VoodooPS2](https://github.com/acidanthera/VoodooPS2), and [WhateverGreen](https://github.com/acidanthera/WhateverGreen).
- Thanks to [apianti](https://sourceforge.net/u/apianti), [blackosx](https://sourceforge.net/u/blackosx), [blusseau](https://sourceforge.net/u/blusseau), [dmazar](https://sourceforge.net/u/dmazar), and [slice2009](https://sourceforge.net/u/slice2009) for providing [Clover](https://github.com/CloverHackyColor/CloverBootloader).
- Thanks to [daliansky](https://github.com/daliansky) for providing [OC-little](https://github.com/daliansky/OC-little).
- Thanks to [hieplpvip](https://github.com/hieplpvip) and [syscl](https://github.com/syscl) for providing sample of DSDT patches.
- Thanks to [OpenIntelWireless](https://github.com/OpenIntelWireless) for providing [IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware).
- Thanks to [RehabMan](https://github.com/RehabMan) for providing [EAPD-Codec-Commander](https://github.com/RehabMan/EAPD-Codec-Commander), [EFICheckDisabler](https://github.com/RehabMan/hack-tools/tree/master/kexts/EFICheckDisabler.kext), [OS-X-Clover-Laptop-Config](https://github.com/RehabMan/OS-X-Clover-Laptop-Config), [OS-X-Null-Ethernet](https://github.com/RehabMan/OS-X-Null-Ethernet), and [SATA-unsupported](https://github.com/RehabMan/hack-tools/tree/master/kexts/SATA-unsupported.kext).
- Thanks to [VoodooI2C](https://github.com/VoodooI2C) for providing [VoodooI2C](https://github.com/VoodooI2C/VoodooI2C).
- Thanks to [One-Key-HiDPI](https://github.com/xzhih/one-key-hidpi)
