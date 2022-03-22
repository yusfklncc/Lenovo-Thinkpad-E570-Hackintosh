<h1 align="center"> macOS on Lenovo Thinkpad E570 </h1>

<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/ThinkPad%20E570.png" alt="Thinkpad E570" width="500">
</p>

<h4 align="center"> OpenCore config for Hackintosh Lenovo Thinkpad E570 </h4>

<p align="center">
<a href="https://www.apple.com/macos/monterey/">
  <img src="https://img.shields.io/badge/macOS-Monterey_v12.3-blue" width="215"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg/releases">
  <img src="https://img.shields.io/badge/OpenCore-0.7.9-9cf" width="155"/> </a>
<a href="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/releases">
  <img src="https://img.shields.io/badge/release-EFI-blue.svg" width="115"/> </a>
</p>
<p align="center">
<a href="https://t.me/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-2CA5E0?logo=Telegram&logoColor=blue" width="150"/> </a>
<a href="https://www.youtube.com/c/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-lightgrey?logo=YouTube&logoColor=red" width="150"/> </a>
<a href="https://www.paypal.com/paypalme/sevenpay">
  <img src="https://img.shields.io/badge/-@sevenpay-2CA5E0?logo=PayPal&logoColor=red" width="140"/> </a>

# Screenshots 📷

<details>
<summary>Monterey</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Monterey.png">
</p>
</details>

<details>
<summary>Big Sur</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Big%20Sur.png">
</p>
</details>

<details>
<summary>Catalina</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Catalina.png">
</p>
</details>

<details>
<summary>Mojave</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Mojave.png">
</p>
</details>

<details>
<summary>High Sierra</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/High%20Sierra.png">
</p>
</details>

<details>
<summary>Sierra</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Sierra.png">
</p>
</details>

# Original Hardware  💻

Type | Spec | Status
:---------|:---------|:----------
Model Name      | Lenovo Thinkpad E570 | ✅
CPU              | Intel(R) Core(TM) i5-7200U CPU @ 2.40GHz Kaby Lake | ✅
RAM           | 8 GB 2400 MHz DDR4 | ✅
Internal Graphics Card | Intel(R) HD Graphics 620 (1 GB) | ✅
Wi-Fi             | Qualcomm Atheros QCA9377 | ❌
Ethernet          | Realtek RTL8111 | ✅
Audio       | Conexant CX20753/4 | ✅
SD Card Reader | O2 Micro SD/MMC | ❌
  
# Modifications  🔨

Type | Spec | Status
:---------|:---------|:----------
| Wi-Fi | Dell Wireless 1820A ac | ✅

## Kext Used 
 
Kext | Info 
:---------|:---------
[Lilu.kext](https://github.com/acidanthera/Lilu) | An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS.
[VirtualSMC.kext](https://github.com/acidanthera/VirtualSMC) | Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning.
[AppleALC.kext](https://github.com/acidanthera/AppleALC) | An open source kernel extension enabling native macOS HD audio for not officially supported codecs without any filesystem modifications.
[USBPorts.kext](https://www.youtube.com/watch?v=rlTDHkPzjAk&t=654s) | Kext to inject mapped USB Ports.
[USBInjectAl](https://github.com/Sniki/OS-X-USB-Inject-All) | Kext to inject USB ports.
[VoodooPS2Controller.kext](https://github.com/acidanthera/VoodooPS2) | Contains updated Voodoo PS/2 Controller, improved Keyboard & Synaptics TouchPad.
[WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen) | Various patches necessary for certain ATI/AMD/Intel/Nvidia GPUs. This is needed for Intel HD 620.
[SMCBatteryManager.kext](https://github.com/acidanthera/VirtualSMC) | Battery Status Monitoring.
[SMCProcessor.kext](https://github.com/acidanthera/VirtualSMC) | Processor Temp Monitoring.
[SMCSuperIO.kext](https://github.com/acidanthera/VirtualSMC) | Fan Reading.
[RealtekRTL8111.kext](https://github.com/Mieze/RTL8111_driver_for_OS_X) | OS X open source driver for the Realtek RTL8111/8168 family.
[AirportBrcmFixup](https://github.com/acidanthera/AirportBrcmFixup) | An open source kernel extension providing a set of patches required for non-native Airport Broadcom Wi-Fi cards.
[BrcmPatchRAM](https://github.com/acidanthera/BrcmPatchRAM) | BrcmPatchRAM kext is a macOS driver which applies PatchRAM updates for Broadcom RAMUSB based devices.
[NVMeFix.kext](https://github.com/acidanthera/NVMeFix) | NVMeFix is a set of patches for the Apple NVMe storage driver, IONVMeFamily.
[CPUFriend.kext](https://github.com/acidanthera/CPUFriend) | A Lilu plug-in for dynamic power management data injection.
[CPUFriendDataProvider.kext](https://github.com/acidanthera/CPUFriend) | A CPUFriend plug-in for CPU power management.
[FeatureUnlock.kext](https://github.com/acidanthera/FeatureUnlock) | Lilu Kernel extension for enabling: Sidecar, NightShift, AirPlay to Mac, Universal Control.
[HibernationFixup.kext](https://github.com/acidanthera/HibernationFixup) | An open source kernel extension providing a sync between RTC variables and NVRAM.
[NoTouchID.kext](https://github.com/al3xtjames/NoTouchID) | Lilu plugin for disabling Touch ID support.
[ECEnabler.kext](https://github.com/1Revenger1/ECEnabler) | Allows reading Embedded Controller fields over 1 byte long.
  
## SSDT Used
  
SSDT | Info
:---------|:---------|:---------
[SSDT-AC.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/AC_Adapter_(SSDT-AC)) | Attaches an AC Adapter Device existing in a Laptop's DSDT to the AppleACPIACAdapter service in the IORegistry of macOS. | [Cosmetic]
  

[SSDT-BATT.aml](https://dortania.github.io/OpenCore-Post-Install/laptop-specific/battery.html#battery-status) | [Functional] Fixes the battery status indicator.
[SSDT-CLICKPAD.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/05_Laptop-specific_Patches/Trackpad_Patches/ThinkPad_Click_and_TrackPad_Patches) | [Functional] Fixes Touchpad Buttons but some error. Customize Touchpad Settings.
[SSDT-DMAC.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/DMA_Controller_(SSDT-DMAC)) | [Cosmetic] Adds Direct Memory Access Controller (DMAC) device to IORegistry.
[SSDT-EC-USBX.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/ec-fix.html#fixing-embedded-controller-ssdt-ecusbx) | [Functional] Adds a fake Embedded Controller (SSDT-EC) and enables USB Power Management (SSDT-EC-USBX).
[SSDR-EXT5-TP-LED.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/04_Fixing_Sleep_and_Wake_Issues/PTSWAK_Sleep_and_Wake_Fix) | [Functional] Fixes ThinkPads breathing light of the Power Button LED will not return to normal after waking up. Also fixes an issue where the F4 microphone indicator status is not normal after waking up on older ThinkPad models.
[SSDT-FIXSHUTDOWN.aml](https://dortania.github.io/OpenCore-Post-Install/usb/misc/shutdown.html#fixing-shutdown-restart) | [Functional] Fixing Shutdows/Restart. Due to a missing S5 call that powers down the controller.
[SSDT-FWHD.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Fake_Firmware_Hub_(SSDT-FWHD)) | [Cosmetic] Adds Fake Firmware Hub Device (FWHD) device to the IORegistry in macOS.
[SSDT-HPET.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/irq.html#fixing-irq-conflicts-ssdt-hpet-oc-patches-plist) | [Functional] Fixes IRQ conflicts. Required for on-board sound to work.
[SSDT-KBD.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/05_Laptop-specific_Patches/Brightness_Key_Shortcuts) | [Functional] Enable Brightness Key Shortcuts with 11. and 12. ACPI Patch. (Using BrightnessKeys.kext with 13. ACPI Patch.
[SSDT-OC-XOSI.aml](https://dortania.github.io/Getting-Started-With-ACPI/ssdt-methods/ssdt-prebuilt.html#trackpad) | [Functional] OS Check Fix patch to simulate a version of Windows for Darwin.
[SSDT-PLUG.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/plug.html#fixing-power-management-ssdt-plug) | [Functional] Allow the kernel's XCPM(XNU's CPU Power Management) to manage CPU's power management.
[SSDT-PMC.aml](https://github.com/corpnewt/SSDTTime) | [Functional] It specifically brings back NVRAM support and requires very little configuration for the end user.
[SSDT-PNLF.aml](https://dortania.github.io/Getting-Started-With-ACPI/Laptops/backlight.html) | [Functional] Adds Backlight Control for Laptop Screens.
[SSDT-PTSWAK.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/04_Fixing_Sleep_and_Wake_Issues/PTSWAK_Sleep_and_Wake_Fix) | [Functional] Comprehensive Sleep and Wake Patch.
[SSDT-PWRB-SLPB_STA0B.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Power_and_Sleep_Button_(SSDT-PWRB:SSDT-SLPB)) | [Functional] Enabling Power and Sleep Buttons.
[SSDT-RTC_STA0F.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/System_Clock_(SSDT-RTC0)) | [Functional] Force-enable the RTC Device.
[SSDT-SBUS-MCHC.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/smbus.html) | [Functional] Fixes System Management Bus and Memory Controller in macOS.

  
# Update History
- ✅ macOS Monterey 12.3
- ✅ macOS Monterey 12.2.1  
- ✅ macOS Monterey 12.0.1
- ✅ macOS Big Sur 11.6.1
- ✅ macOS Big Sur 11.0.1
- ✅ macOS Catalina 10.15.7
- ✅ macOS Mojave 10.14.6
- ✅ macOS High Sierra 10.13.6
- ✅ macOS Sierra 10.12.6

# What's working  💻
Type | Status
:---------|:---------
Turbo boost and CPU frequency stage |  ✅  
Intel HD Graphics 620              |  ✅  
Brightness control                  |  ✅  
HDMI                                |  ✅  
Audio Conexant CX20753/4            |  ✅  
Realtek Ethernet RTL8111            |  ✅  
DW1820A Wi-Fi and Bluetooth, Airdrop, Handoff, SideCar, iMessage...         |  ✅  
USB 3.0 and Type-C (with Port Map)        |  ✅  
Touchpad (14 gestures are working)   |  ✅  
Battery status   |  ✅  
Camera   |  ✅  
S3 Sleep / Wake   |  ✅  
S4 Hibernation / Wake   |  ✅  
Shutdown / Reboot   |  ✅  
Fn shortcut keys   |  ✅  
 
# What's you have to do  💻
Type | Info | Status
:---------|:---------|:----------
Micro SD Card Reader | Not working in OpenCore. You have to patch DSDT or use CLOVER | ⚠️ 
SMBIOS Settings  | With OpenCore Configurator you should definitely set your SMBIOS settings and ROM value because the config does not contain SMBIOS information MacBook Pro 14.1. ROM value is your ethernet MAC address. Be sure your ethernet is en0 in Hackintool. |  ⚠️
Rename config    | If you install Monterey+, you can delete BrcmBluetoothInjector.kext in OC/Kexts. If you install Big Sur-, you can delete BlueToolFixup.kext in OC/Kexts. | ⚠️ 
  
## Credits
 - [Dortania](https://dortania.github.io) for developing OpenCore.
 - [Apple](https://www.apple.com) for macOS.
 - [Acidanthera](https://github.com/acidanthera) for most of the kexts.
 - [RehabMan](https://github.com/RehabMan) for battery patches.
 - [Sniki](https://github.com/Sniki) for USB kext.
 - And anyone else that helped to develop and improve hackintoshing.

<h1 align="center"> Donate - Bağış </h1>
<p align="center">
<a href="https://github.com/yusufklncc/yusfklncc/blob/main/Donate%20-%20Ba%C4%9F%C4%B1%C5%9F.md">
  <img src="https://github.com/yusufklncc/yusfklncc/blob/main/Resources/Donate.png" width="300">
