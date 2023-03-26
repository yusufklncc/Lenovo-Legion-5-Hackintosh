<h1 align="center"> macOS on Lenovo Legion 5 15IMH05H </h1>

<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/blob/main/Images/macOS%20Lenovo%20Legion%205.png">
</p>

<h4 align="center"> OpenCore config for Hackintosh Lenovo Legion 5 15IMH05H </h4>

<p align="center">
<a href="https://www.apple.com/macos/ventura/">
  <img src="https://img.shields.io/badge/macOS-Ventura%2013.0.1-orange" width="197"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg/releases">
  <img src="https://img.shields.io/badge/OpenCore-0.9.0-9cf" width="155"/> </a>
<a href="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/releases">
  <img src="https://img.shields.io/badge/release-EFI-blue.svg" width="115"/> </a>
<a href="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/issues"> 
  <img src="https://img.shields.io/github/issues/yusufklncc/Lenovo-Legion-5-Hackintosh" width="145"/> </a>
</p>
<p align="center">
<a href="https://t.me/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-2CA5E0?logo=Telegram&logoColor=blue" width="150"/> </a>
<a href="https://www.youtube.com/c/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-red?logo=YouTube&logoColor=white" width="150"/> </a>
<a href="https://www.paypal.com/paypalme/sevenpay">
  <img src="https://img.shields.io/badge/-@sevenpay-2CA5E0?logo=PayPal&logoColor=red" width="140"/> </a>
<a href="https://www.buymeacoffee.com/yusufklncc">
  <img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" width="150"/> </a>

## Contents
  - [Screenshots](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#screenshots-)
  - [Original Hardware](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#original-hardware--)
  - [macOS Update History](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#macos-update-history)
  - [What's working](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#whats-working--)
  - [What's not working](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#whats-not-working--)
  - [What's you have to do](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#whats-you-have-to-do--)
  - [Disable NVIDIA Card](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/blob/main/README.md#disable-nvidia-card)
  - [Kexts Used](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#kexts-used)
  - [SSDTs Used](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#ssdts-used)
  - [Credits](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#credits)
  - [Donate](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#-donate---ba%C4%9F%C4%B1%C5%9F-)

## Screenshots 📷

### CPU Usage and Temperature  
- Normal

  <img src="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/blob/main/Images/Normal%20CPU%20Frequency%20and%20Temperature.png" width="300">
  <img src="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/blob/main/Images/Normal%20CPU%20Usage.png" width="400">
  
- Maximum

  <img src="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/blob/main/Images/Max%20CPU%20Frequency%20and%20Temperature.png" width="300">
  <img src="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/blob/main/Images/Max%20CPU%20Usage.png" width="400">  
  
### Geekbench
- CPU
  - <img src="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/blob/main/Images/CPU%20Geekbench.png" width="500">
  - browser.geekbench.com/v5/cpu/14625598
  
  
- OpenCL
  - <img src="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/blob/main/Images/OpenCL.png" width="500">
  - browser.geekbench.com/v5/compute/4746733
  
- Metal
  - <img src="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/blob/main/Images/Metal.png" width="500">
  - browser.geekbench.com/v5/compute/4746748
  
<details>
<summary>Big Sur</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/blob/main/Images/macOS/macOS%20Big%20Sur.png">
</p>
</details>
 
## Original Hardware  💻

Type | Spec | Status
:---------|:---------|:----------
Model Name      | Lenovo Legion 5 15IMH05H | ✅
CPU              | Intel(R) Core(TM) i7-10750H CPU @ 2.60GHz Comet Lake | ✅
RAM           | 16 GB 2933 MHz DDR4 | ✅
Internal Graphics Card | Intel(R) UHD Graphics 630 (1 GB) | ✅
External Graphics Card | NVIDIA GeForce RTX 2060 | ❌
Wi-Fi             | Intel AX201 Wi-Fi 6 (802.11ax) | ✅
Ethernet          | Realtek RTL8111 | ✅
Audio       | Realtek ALC 257 | ✅

## macOS Update History
- ✅ macOS Ventura 13.0
- ✅ macOS Monterey 12.6
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
Brightness control | Brightness level is coming from Windows. If you set your brightness %50 in Windows. Your macOS level is %50. Use Lunar.app | ⚠️
HDMI | Beacuse it connected to RTX2060 | ❌
Airdrop, Sidecar | Beacuse Intel Wi-Fi Doesn't Support | ❌

## What's you have to do  💻
Type | Info | Status
:---------|:---------|:----------
SMBIOS Settings  | With [GenSMBIOS] you should definitely set your SMBIOS settings and ROM value for iCloud and Apple services. ROM value is your ethernet MAC address. Be sure your ethernet is en0 in Hackintool. |  ⚠️

  
## Disable NVIDIA Card
  - Erase ## values config/DeviceProperties -> PciRoot(0x0)/Pci(0x1,0x0)/Pci(0x0,0x0) 
  

## Kexts Used 
 
Kext | Info 
:---------|:---------
[Lilu](https://github.com/acidanthera/Lilu) | An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS.
[VirtualSMC](https://github.com/acidanthera/VirtualSMC) | Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning.
[WhateverGreen](https://github.com/acidanthera/WhateverGreen) | Various patches necessary for certain ATI/AMD/Intel/Nvidia GPUs. This is needed for Intel UHD 630.
[SMCBatteryManager](https://github.com/acidanthera/VirtualSMC) | Battery Status Monitoring.
[SMCProcessor](https://github.com/acidanthera/VirtualSMC) | Processor Temp Monitoring.
[AppleALC](https://github.com/acidanthera/AppleALC) | An open source kernel extension enabling native macOS HD audio for not officially supported codecs without any filesystem modifications.
[VerbStub](https://github.com/hackintosh-stuff/ComboJack) | Fixes jack headphone audio and microphone.
[USBPorts](https://www.youtube.com/watch?v=rlTDHkPzjAk&t=654s) | Kext to inject mapped USB Ports.
[USBWakeFixup](https://github.com/osy/USBWakeFixup) | This extension is a workaround for that issue by creating a fake ACPI device with the right wakeup params.
[CPUFriend](https://github.com/acidanthera/CPUFriend) | A Lilu plug-in for dynamic power management data injection.
[CPUFriendDataProvider](https://github.com/acidanthera/CPUFriend) | A CPUFriend plug-in for CPU power management.
[NVMeFix](https://github.com/acidanthera/NVMeFix) | NVMeFix is a set of patches for the Apple NVMe storage driver, IONVMeFamily.
[RestrictEvents](https://github.com/acidanthera/RestrictEvents) | Lilu Kernel extension for blocking unwanted processes causing compatibility issues on different hardware and unlocking the support for certain features restricted to other hardware.
[VoodooI2C](https://github.com/VoodooI2C/VoodooI2C) | VoodooI2C is a project consisting of macOS kernel extensions that add support for I2C bus devices. 
[VoodooPS2Controller](https://github.com/acidanthera/VoodooPS2) | Contains updated Voodoo PS/2 Controller, improved Keyboard & Synaptics TouchPad.
[RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X) | OS X open source driver for the Realtek RTL8111/8168 family.
[AirportItlwm](https://github.com/OpenIntelWireless/itlwm) | An Intel Wi-Fi Adapter Kernel Extension for macOS.
[IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | Kernel Extension that uploads Intel Wireless Bluetooth Firmware to provide native Bluetooth in macOS.
[BlueToolFixup](https://github.com/acidanthera/BrcmPatchRAM) | Injecting bluetooth firmware on Monterey+.
[HibernationFixup](https://github.com/acidanthera/HibernationFixup) | An open source kernel extension providing a sync between RTC variables and NVRAM.
[FeatureUnlock](https://github.com/acidanthera/FeatureUnlock) | Lilu Kernel extension for enabling: Sidecar, NightShift, AirPlay to Mac, Universal Control.
  
## SSDTs Used
  
SSDT | Info | Status
:---------|:---------|:---------
[SSDT-AC.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/AC_Adapter_(SSDT-AC)) | Attaches an AC Adapter Device existing in a Laptop's DSDT to the AppleACPIACAdapter service in the IORegistry of macOS. | [Cosmetic]
[SSDT-ARTC.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Fake_Apple_RTC_(SSDT-ARTC)) | Adds ARTC device to IORegistry in macOS. | [Cosmetic]
[SSDT-AWAC.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/System_Clock_(SSDT-AWAC)) | Hotpatches for enabling RTC and disabling AWAC system clock at the same time. | [Functional]
[SSDT-dGPU-Off.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/02_Disabling_Devices/Disabling_unsupported_GPUs) | %100 FAN ISSUE CARD DISABLED WITH DEVICE PROPERTIES.
[SSDT-DMAC.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/DMA_Controller_(SSDT-DMAC)) | Adds Direct Memory Access Controller (DMAC) device to IORegistry. | [Cosmetic]
[SSDT-FWHD.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Fake_Firmware_Hub_(SSDT-FWHD)) | Adds Fake Firmware Hub Device (FWHD) device to the IORegistry in macOS. | [Cosmetic]
[SSDT-HPET.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/irq.html#fixing-irq-conflicts-ssdt-hpet-oc-patches-plist) | Fixes IRQ conflicts. Required for on-board sound to work. | [Functional]
[SSDT-EC-USBX.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/ec-fix.html#fixing-embedded-controller-ssdt-ecusbx) | Adds a fake Embedded Controller (SSDT-EC) and enables USB Power Management (SSDT-EC-USBX). | [Functional]
[SSDT-GPRW.aml](https://dortania.github.io/OpenCore-Post-Install/usb/misc/instant-wake.html#gprw-uprw-lanc-instant-wake-patch) | Fixes instant wake if either USB or power states change while sleeping. | [Functional]
[SSDT-OCGPI0-GPHD.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/OCI2C-GPIO_Patch) | The presence of a GPIO device is usually required for a I2C TrackPads to function properly. | [Functional]
[SSDT-OC-XOSI.aml](https://dortania.github.io/Getting-Started-With-ACPI/ssdt-methods/ssdt-prebuilt.html#trackpad) | OS Check Fix patch to simulate a version of Windows for Darwin. | [Functional]
[SSDT-PLUG.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/plug.html#fixing-power-management-ssdt-plug) | Allow the kernel's XCPM(XNU's CPU Power Management) to manage CPU's power management. | [Functional]
[SSDT-PNLF-CFL.aml](https://dortania.github.io/Getting-Started-With-ACPI/Laptops/backlight.html) | Adds Backlight Control for Laptop Screens. DISABLED | [Functional]
[SSDT-PS2K.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/05_Laptop-specific_Patches/Brightness_Key_Shortcuts) | Enable Brightness Key Shortcuts. | [Functional]
[SSDT-PTSWAK.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/04_Fixing_Sleep_and_Wake_Issues/PTSWAK_Sleep_and_Wake_Fix) | Comprehensive Sleep and Wake Patch. | [Functional]
[SSDT-SLPB.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Power_and_Sleep_Button_(SSDT-PWRB:SSDT-SLPB)) | Enabling Sleep Button. | [Functional]
[SSDT-SBUS-MCHC.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/smbus.html) | Fixes System Management Bus and Memory Controller in macOS. | [Functional]
[SSDT-XSPI.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Intel_PCH_SPI_Controller_(SSDT-XSPI)) | Adds Platform Controller Hub (PCH) to IORegistry.


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
