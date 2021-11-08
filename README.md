<!-- omit in toc -->
# <img align="left" src="https://github.com/yusfklncc/HP-EliteBook-840-G5-Hackintosh/blob/main/Apple.png" width="30px" alt="preview">macOS on Lenovo Thinkpad E570

<h3> 
    English
</h3>

<img align="right" src="https://github.com/relaxewdy/Lenovo-Thinkpad-E570-Hackintosh/blob/main/E570.png?raw=true" width="300px" alt="preview">

OpenCore config for Hackintosh OpenCore Lenovo Thinkpad E570.

[![macOS](https://img.shields.io/badge/macOS-12.0.1-orange)](https://www.apple.com/tr/macos/big-sur/)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.7.5-9cf)](https://github.com/acidanthera/OpenCorePkg)
[![release](https://img.shields.io/badge/download-lastest%20version-blue.svg)](https://github.com/relaxewdy/Thinkpad-E570-Hackintosh-OpenCore/releases)

## Screenshot
<details>
<summary>Big Sur</summary>

![](https://github.com/relaxewdy/Lenovo-Thinkpad-E570-Hackintosh/blob/main/BigSur.png)

</details>

<!-- omit in toc -->
## Hardware

| **LENOVO** | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Model Name      | Lenovo Thinkpad E570      |
| CPU              | Intel(R) Core(TM) i5-7200U CPU @ 2.40GHz Kaby Lake             |
| RAM           | 8 GB 2400 MHz DDR4    |
| Internal Graphics Card | Intel(R) HD Graphics 620 (1 GB)                     |
| Wi-Fi             | QCA9377 (replaced with DW1820A) |
| Ethernet          | Realtek RTL8111            |
| Audio       | Conexant CX20753/4                       |

# Update History
- [x] macOS Monterey 12.0.1
- [x] macOS Big Sur 11.6.1
- [x] macOS Big Sur 11.0.1

# What's Working?
|                                 |                                    |
| -----------------------------------  | -------- |
|  Turbo boost and CPU frequency stage |  ✅  |
|  Intel HD Graphics 620              |  ✅  |
|  Brightness control                  |  ✅  |
|  HDMI                                |  ✅  |
|  Audio Conexant CX20753/4            |  ✅  |
|  Realtek Ethernet RTL8111            |  ✅  | 
|  DW1820A Wi-Fi and Bluetooth, Airdrop, Handoff, SideCar, iMessage...         |  ✅  |
|  USB 3.0 and Type-C (with Port Map)        |  ✅  |
|  Touchpad (14 gestures are working)   |  ✅  |
|  Battery status   |  ✅  |
|  Camera   |  ✅  |
|  S3 Sleep / Wake   |  ✅  |
|  S4 Hibernation / Wake   |  ✅  |
|  Shutdown / Reboot   |  ✅  |
|  Fn shortcut keys   |  ✅  |
 
# What You Have to Do?
|                                 |                                    |
| -----------------------------------  | -------- |
|  SMBIOS Settings  | ⚠️ |
|  Rename config    | ⚠️ |

If you install Monterey+, you can delete BrcmBluetoothInjector.kext in OC/Kexts. 

If you install Big Sur-, you can delete BlueToolFixup.kext in OC/Kexts.
With OpenCore Configrator you should definitely set your SMBIOS settings because the config does not contain SMBIOS information MacBook Pro 14.1
