<h1 align="center"> macOS on Lenovo Legion 5 15IMH05H </h1>

<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/blob/main/Images/Legion%205.png" alt="Legion 5">
</p>

<h4 align="center"> OpenCore config for Hackintosh Lenovo Legion 5 15IMH05H </h4>

<p align="center">
<a href="https://www.apple.com/macos/monterey/">
  <img src="https://img.shields.io/badge/macOS-Monterey_v12.3-blue" width="215"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg/releases">
  <img src="https://img.shields.io/badge/OpenCore-0.7.9-9cf" width="155"/> </a>
<a href="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/releases">
  <img src="https://img.shields.io/badge/release-EFI-blue.svg" width="115"/> </a>
</p>
<p align="center">
<a href="https://t.me/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-2CA5E0?logo=Telegram&logoColor=blue" width="150"/> </a>
<a href="https://www.youtube.com/c/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-lightgrey?logo=YouTube&logoColor=red" width="150"/> </a>
<a href="https://www.paypal.com/paypalme/sevenpay">
  <img src="https://img.shields.io/badge/-@sevenpay-2CA5E0?logo=PayPal&logoColor=red" width="140"/> </a>

## Contents
  - [Screenshots](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#screenshots-)
  - [Original Hardware](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#original-hardware--)
  - [macOS Update History](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#macos-update-history)
  - [What's working](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#whats-working--)
  - [What's not working](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#whats-not-working--)
  - [What's you have to do](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#whats-you-have-to-do--)
  - [Credits](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#credits)
  - [Donate](https://github.com/yusufklncc/yusfklncc/blob/main/Donate%20-%20Bağış.md)

## Screenshots 📷

### Big Sur</summary>
  <img src="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/blob/main/Images/macOS/macOS%20Big%20Sur.png">
 
## Original Hardware  💻

Type | Spec | Status
:---------|:---------|:----------
Model Name      | Lenovo Legion 5 15IMH05H | ✅
CPU              | Intel(R) Core(TM) i7-10750H CPU @ 2.60GHz Comet Lake | ✅
External Graphics Card | NVIDIA GeForce RTX 2060 | ❌
RAM           | 16 GB 2933 MHz DDR4 | ✅
Internal Graphics Card | Intel(R) UHD Graphics 630 (1 GB) | ✅
Wi-Fi             | Intel AX201 Wi-Fi 6 (802.11ax) | ✅
Ethernet          | Realtek RTL8111 | ✅
Audio       | Realtek ALC 257 | ✅

## macOS Update History
- ✅ macOS Monterey 12.0.1
- ✅ macOS Big Sur 11.6.1
- ✅ macOS Big Sur 11.0.1

## What's working  💻
Type | Status
:---------|:----------
Turbo boost and CPU frequency stage |  ✅  
Intel UHD Graphics 630              |  ✅  
Audio Realtek ALC 257            |  ✅  
Realtek Ethernet RTL8111            |  ✅  
Intel AX201 Wi-Fi and Bluetooth, Handoff, iMessage...         |  ✅  
USB 3.0 and Type-C (with Port Map)        |  ✅  
Touchpad (14 gestures are working)   |  ✅  
Battery status   |  ✅  
Camera   |  ✅  
S3 Sleep / Wake   |  ✅  
S4 Hibernation / Wake   |  ✅  
Shutdown / Reboot   |  ✅  
Fn shortcut keys   |  ✅  
 
## What's not working  💻
Type | Info | Status
:---------|:---------|:----------
Brightness control | Brightness level is coming from Windows. If you set your brightness %50 in Windows. Your macOS level is %50 | ⚠️
HDMI | Beacuse it connected to RTX2060 | ❌
Airdrop, Sidecar | Beacuse Intel Wi-Fi Doesn't Support | ❌

## What's you have to do  💻
Type | Info | Status
:---------|:---------|:----------
SMBIOS Settings  | With OpenCore Configurator you should definitely set your SMBIOS settings and ROM value because the config does not contain SMBIOS information MacBook Pro 16.4. ROM value is your ethernet MAC address. Be sure your ethernet is en0 in Hackintool. |  ⚠️
Rename config    | If you install Monterey+, you can delete BrcmBluetoothInjector.kext in OC/Kexts. If you install Big Sur-, you can delete BlueToolFixup.kext in OC/Kexts. | ⚠️ 

## Kext Used 
 
Kext | Info 
:---------|:---------
[Lilu.kext](https://github.com/acidanthera/Lilu) | An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS.
[VirtualSMC.kext](https://github.com/acidanthera/VirtualSMC) | Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning.
[WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen) | Various patches necessary for certain ATI/AMD/Intel/Nvidia GPUs. This is needed for Intel UHD 630.
[AppleALC.kext](https://github.com/acidanthera/AppleALC) | An open source kernel extension enabling native macOS HD audio for not officially supported codecs without any filesystem modifications.
[VerbStub.kext](https://github.com/hackintosh-stuff/ComboJack) | Fixes jack headphone audio and microphone.
[USBPorts.kext](https://www.youtube.com/watch?v=rlTDHkPzjAk&t=654s) | Kext to inject mapped USB Ports.
[USBInjectAl](https://github.com/Sniki/OS-X-USB-Inject-All) | Kext to inject USB ports.
[VoodooPS2Controller.kext](https://github.com/acidanthera/VoodooPS2) | Contains updated Voodoo PS/2 Controller, improved Keyboard & Synaptics TouchPad.
[ACPIBatteryManager.kext](https://bitbucket.org/RehabMan/os-x-acpi-battery-driver/downloads/) | Battery Status Monitoring.
[SMCProcessor.kext](https://github.com/acidanthera/VirtualSMC) | Processor Temp Monitoring.
[RealtekRTL8111.kext](https://github.com/Mieze/RTL8111_driver_for_OS_X) | OS X open source driver for the Realtek RTL8111/8168 family.
[AirportBrcmFixup](https://github.com/acidanthera/AirportBrcmFixup) | An open source kernel extension providing a set of patches required for non-native Airport Broadcom Wi-Fi cards.
[BrcmPatchRAM](https://github.com/acidanthera/BrcmPatchRAM) | BrcmPatchRAM kext is a macOS driver which applies PatchRAM updates for Broadcom RAMUSB based devices.
[BrightnessKeys](https://github.com/acidanthera/BrightnessKeys) | Automatic handling of brightness keys based on ACPI Specification.
[NVMeFix.kext](https://github.com/acidanthera/NVMeFix) | NVMeFix is a set of patches for the Apple NVMe storage driver, IONVMeFamily.
[CPUFriend.kext](https://github.com/acidanthera/CPUFriend) | A Lilu plug-in for dynamic power management data injection.
[CPUFriendDataProvider.kext](https://github.com/acidanthera/CPUFriend) | A CPUFriend plug-in for CPU power management.
[FeatureUnlock.kext](https://github.com/acidanthera/FeatureUnlock) | Lilu Kernel extension for enabling: Sidecar, NightShift, AirPlay to Mac, Universal Control.
[HibernationFixup.kext](https://github.com/acidanthera/HibernationFixup) | An open source kernel extension providing a sync between RTC variables and NVRAM.
[NoTouchID.kext](https://github.com/al3xtjames/NoTouchID) | Lilu plugin for disabling Touch ID support.
  
## SSDT Used
  
SSDT | Info | Status
:---------|:---------|:---------
[SSDT-AWAC.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/System_Clock_(SSDT-AWAC)) | Hotpatches for enabling RTC and disabling AWAC system clock at the same time. | [Functional]
[SSDT-EC-USBX.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/ec-fix.html#fixing-embedded-controller-ssdt-ecusbx) | Adds a fake Embedded Controller (SSDT-EC) and enables USB Power Management (SSDT-EC-USBX). | [Functional]
[SSDT-GPI0-GPHD.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/OCI2C-GPIO_Patch) | The presence of a GPIO device is usually required for a I2C TrackPads to function properly. | [Functional]
[SSDT-GPRW.aml](https://dortania.github.io/OpenCore-Post-Install/usb/misc/instant-wake.html#gprw-uprw-lanc-instant-wake-patch) | Fixes instant wake if either USB or power states change while sleeping. | [Functional]
[SSDT-HPET.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/irq.html#fixing-irq-conflicts-ssdt-hpet-oc-patches-plist) | Fixes IRQ conflicts. Required for on-board sound to work. | [Functional]
[SSDT-OC-XOSI.aml](https://dortania.github.io/Getting-Started-With-ACPI/ssdt-methods/ssdt-prebuilt.html#trackpad) | OS Check Fix patch to simulate a version of Windows for Darwin. | [Functional]
[SSDT-PLUG.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/plug.html#fixing-power-management-ssdt-plug) | Allow the kernel's XCPM(XNU's CPU Power Management) to manage CPU's power management. | [Functional]
[SSDT-PNLF-CFL.aml](https://dortania.github.io/Getting-Started-With-ACPI/Laptops/backlight.html) | Adds Backlight Control for Laptop Screens. | [Functional]
[SSDT-PS2K.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/05_Laptop-specific_Patches/Brightness_Key_Shortcuts) | Enable Brightness Key Shortcuts. | [Functional]
[SSDT-SBUS-MCHC.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/smbus.html) | Fixes System Management Bus and Memory Controller in macOS. | [Functional]

## Credits
 - [Dortania](https://dortania.github.io) for developing OpenCore.
 - [Apple](https://www.apple.com) for macOS.
 - [Acidanthera](https://github.com/acidanthera) for most of the kexts.
 - [RehabMan](https://github.com/RehabMan) for battery patches.
 - [Sniki](https://github.com/Sniki) for USB kext.
 - And anyone else that helped to develop and improve hackintoshing.

<h1 align="center"> Donate - Bağış </h1>
<p align="center">
<a href="https://github.com/yusufklncc/yusufklncc/blob/main/Donate%20-%20Ba%C4%9F%C4%B1%C5%9F.md">
  <img src="https://github.com/yusufklncc/yusufklncc/blob/main/Resources/Donate.png" width="300">
