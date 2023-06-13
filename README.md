<h1 align="center"> macOS on Lenovo Legion 5 15IMH05H </h1>

<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/blob/main/Images/macOS%20Lenovo%20Legion%205.png" width="700"/>
</p>

<h4 align="center"> OpenCore config for Hackintosh Lenovo Legion 5 15IMH05H </h4>

<p align="center">
<a href="https://www.apple.com/macos/sonoma-preview/">
  <img src="https://img.shields.io/badge/macOS-Sonoma-green" width="170"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg/releases">
  <img src="https://img.shields.io/badge/OpenCore-0.9.3-9cf" width="155"/> </a>
<a href="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/releases">
  <img src="https://img.shields.io/badge/release-EFI-blue.svg" width="115"/> </a>
<a href="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/issues"> 
  <img src="https://img.shields.io/github/issues/yusufklncc/Lenovo-Legion-5-Hackintosh" width="145"/> </a>
</p>
<p align="center">
<a href="https://t.me/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-2CA5E0?logo=Telegram&logoColor=white" width="150"/> </a>
<a href="https://www.youtube.com/c/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-red?logo=YouTube&logoColor=white" width="150"/> </a>
<a href="https://www.paypal.com/paypalme/sevenpay">
  <img src="https://img.shields.io/badge/-@sevenpay-white?logo=PayPal" width="140"/> </a>
<a href="https://www.buymeacoffee.com/yusufklncc">
  <img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" width="150"/> </a>

## Contents
  - [Screenshots](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#screenshots-)
  - [Original Hardware](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#original-hardware--)
  - [macOS Update History](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#macos-update-history)
  - [What's working](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#whats-working--)
  - [What's not working](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#whats-not-working--)
  - [What's you have to do](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#whats-you-have-to-do--)
  - [Kexts Used](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#kexts-used)
  - [SSDTs Used](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#ssdts-used)
  - [Installation](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#installation-steps)
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
- ✅ macOS Sonoma 14.0 (not tested)
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
Audio Realtek ALC 257 - layout-id: 11            |  ✅  
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
Brightness control | NOT TESTED, Use Lunar.app | ⚠️
HDMI | Beacuse it connected to RTX2060 | ❌
Airdrop, Sidecar | Beacuse Intel Wi-Fi Doesn't Support | ❌

## What's you have to do  💻
Type | Status
:---------|:---------
Follow [macOS Installation steps](https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh#installation-steps)  | ⚠️ 

## Kexts Used 
 
Kext | Info | MinKernel | MaxKernel
:---------|:---------|:---------|:---------
[Lilu](https://github.com/acidanthera/Lilu) | An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS. | 8.0.0 |  
[VirtualSMC](https://github.com/acidanthera/VirtualSMC) | Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning. | 8.0.0 |  
[SMCBatteryManager](https://github.com/acidanthera/VirtualSMC) | Battery Status Monitoring. | 8.0.0 |  
[SMCProcessor](https://github.com/acidanthera/VirtualSMC) | Processor Temp Monitoring. | 11.0.0 |  
[WhateverGreen](https://github.com/acidanthera/WhateverGreen) | Various patches necessary for certain ATI/AMD/Intel/Nvidia GPUs. This is needed for Intel UHD 630. | 10.0.0 |  
[AppleALC](https://github.com/acidanthera/AppleALC) | An open source kernel extension enabling native macOS HD audio for not officially supported codecs without any filesystem modifications. | 8.0.0 |  
[VerbStub](https://github.com/hackintosh-stuff/ComboJack) | Fixes jack headphone audio and microphone. | 8.0.0 |  
[CPUFriend](https://github.com/acidanthera/CPUFriend) | A Lilu plug-in for dynamic power management data injection. | 10.0.0 |  
[CpuTscSync](https://github.com/acidanthera/CpuTscSync) | Needed for syncing TSC on some of Intel's HEDT and server motherboards, without this macOS may be extremely slow or even unbootable. | 12.0.0 | 
[NoTouchID](https://github.com/al3xtjames/NoTouchID) | Lilu plugin for disabling Touch ID support. | 17.0.0 | 19.5.9
[NVMeFix](https://github.com/acidanthera/NVMeFix) | NVMeFix is a set of patches for the Apple NVMe storage driver, IONVMeFamily. | 18.0.0 |  22.9.9
[FeatureUnlock](https://github.com/acidanthera/FeatureUnlock) | Lilu Kernel extension for enabling: Sidecar, NightShift, AirPlay to Mac, Universal Control. | 16.5.0 |  
[RestrictEvents](https://github.com/acidanthera/RestrictEvents) | Lilu Kernel extension for blocking unwanted processes causing compatibility issues on different hardware and unlocking the support for certain features restricted to other hardware. | 16.0.0 |  
[HibernationFixup](https://github.com/acidanthera/HibernationFixup) | An open source kernel extension providing a sync between RTC variables and NVRAM. | 16.0.0 |  
[VoodooI2C](https://github.com/VoodooI2C/VoodooI2C) | VoodooI2C is a project consisting of macOS kernel extensions that add support for I2C bus devices.  | 18.0.0 | 
[VoodooI2CHID](https://github.com/VoodooI2C/VoodooI2C) | Multitouch HID. Can be used with I2C/USB Touchscreens and Trackpads  | 18.0.0 | 
[VoodooPS2Controller](https://github.com/acidanthera/VoodooPS2) | Contains updated Voodoo PS/2 Controller, improved Keyboard & Synaptics TouchPad. | 15.0.0 | 
[itlwm](https://github.com/OpenIntelWireless/itlwm) | An Intel Wi-Fi Adapter Kernel Extension for macOS. + Heliport | 23.0.0 |  23.9.9
[AirportItlwm](https://github.com/OpenIntelWireless/itlwm) | An Intel Wi-Fi Adapter Kernel Extension for macOS. |  |  22.9.9
[IntelBTPatcher](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | Bluetooth modules that support Bluetooth 5.X be able to connect to Bluetooth 4.X devices. | 21.0.0 |  
[IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | Kernel Extension that uploads Intel Wireless Bluetooth Firmware to provide native Bluetooth in macOS.
[IntelBluetoothInjector](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | Injecting bluetooth firmware. |  | 20.9.9
[BlueToolFixup](https://github.com/acidanthera/BrcmPatchRAM) | Injecting bluetooth firmware. | 21.0.0 |  
[RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X) | OS X open source driver for the Realtek RTL8111/8168 family. |  |  
[HoRNDIS9.2](https://github.com/jwise/HoRNDIS) | Android USB Tethering. |  |  
[USBPorts](https://www.youtube.com/watch?v=rlTDHkPzjAk&t=654s) | Kext to inject mapped USB Ports. |  |  

## SSDTs Used
  
SSDT | Info | Status
:---------|:---------|:---------
[SSDT-PTSWAK](https://github.com/5T33Z0/OC-Little-Translated/tree/main/04_Fixing_Sleep_and_Wake_Issues/PTSWAK_Sleep_and_Wake_Fix) | Comprehensive Sleep and Wake Patch. | Functional
[SSDT-EXT4](https://github.com/5T33Z0/OC-Little-Translated/tree/main/04_Fixing_Sleep_and_Wake_Issues) | Comprehensive Sleep and Wake Patch. | Functional
[SSDT-AC](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/AC_Adapter_(SSDT-AC)) | Attaches an AC Adapter Device existing in a Laptop's DSDT to the AppleACPIACAdapter service in the IORegistry of macOS. | Cosmetic
[SSDT-ARTC](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Fake_Apple_RTC_(SSDT-ARTC)) | Adds ARTC device to IORegistry in macOS. | Cosmetic
[SSDT-AWAC](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/System_Clock_(SSDT-AWAC)) | Hotpatches for enabling RTC and disabling AWAC system clock at the same time. | Functional
[SSDT-DGPU](https://github.com/5T33Z0/OC-Little-Translated/tree/main/02_Disabling_Devices/Disabling_unsupported_GPUs) | Disables NVIDIA GPU for better battery performance. | Functional
[SSDT-DMAC](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/DMA_Controller_(SSDT-DMAC)) | Adds Direct Memory Access Controller (DMAC) device to IORegistry. | Cosmetic
[SSDT-EC-USBX](https://dortania.github.io/Getting-Started-With-ACPI/Universal/ec-fix.html#fixing-embedded-controller-ssdt-ecusbx) | Adds a fake Embedded Controller (SSDT-EC) and enables USB Power Management (SSDT-EC-USBX). | Functional
[SSDT-FWHD](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Fake_Firmware_Hub_(SSDT-FWHD)) | Adds Fake Firmware Hub Device (FWHD) device to the IORegistry in macOS. | Cosmetic
[SSDT-HPET](https://dortania.github.io/Getting-Started-With-ACPI/Universal/irq.html#fixing-irq-conflicts-ssdt-hpet-oc-patches-plist) | Fixes IRQ conflicts. Required for on-board sound to work. | Functional
[SSDT-GPRW](https://dortania.github.io/OpenCore-Post-Install/usb/misc/instant-wake.html#gprw-uprw-lanc-instant-wake-patch) | Fixes instant wake if either USB or power states change while sleeping. | Functional
[SSDT-I2C](https://github.com/5T33Z0/OC-Little-Translated/tree/main/05_Laptop-specific_Patches/Trackpad_Patches/I2C_TrackPad_Patches) | Fixes Touchpad | Functional
[SSDT-OCGPI0-GPHD](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/OCI2C-GPIO_Patch) | The presence of a GPIO device is usually required for a I2C TrackPads to function properly. | Functional
[SSDT-OC-XOSI](https://dortania.github.io/Getting-Started-With-ACPI/ssdt-methods/ssdt-prebuilt.html#trackpad) | OS Check Fix patch to simulate a version of Windows for Darwin. | Functional
[SSDT-PLUG](https://dortania.github.io/Getting-Started-With-ACPI/Universal/plug.html#fixing-power-management-ssdt-plug) | Allow the kernel's XCPM(XNU's CPU Power Management) to manage CPU's power management. | Functional
[SSDT-PNLF-CFL](https://dortania.github.io/Getting-Started-With-ACPI/Laptops/backlight.html) | Adds Backlight Control for Laptop Screens. DISABLED | Functional
[SSDT-PS2K](https://github.com/5T33Z0/OC-Little-Translated/tree/main/05_Laptop-specific_Patches/Brightness_Key_Shortcuts) | Enable Brightness Key Shortcuts. | Functional
[SSDT-SBUS-MCHC](https://dortania.github.io/Getting-Started-With-ACPI/Universal/smbus.html) | Fixes System Management Bus and Memory Controller in macOS. | Functional
[SSDT-SLPB](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Power_and_Sleep_Button_(SSDT-PWRB:SSDT-SLPB)) | Enabling Sleep Button. | Functional
[SSDT-XSPI](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Intel_PCH_SPI_Controller_(SSDT-XSPI)) | Adds Platform Controller Hub (PCH) to IORegistry. | Cosmetic

## boot-args Used
boot-arg | Info
:---------|:---------
-v | Enables verbose.
darkwake=2 | Disables darkwake.
swd_panic=1 | Avoids issue where going to sleep results in a reboot
-noDC9 | Fixes sleep issues.
-lilubetaall | Required for macOS Sonoma right now.

## Installation Steps

### Downloading OSX Image

- Click to OneDrive link and download it.
  - [Ventura](https://github.com/yusufklncc/Hackintosh-for-All-Computers#-macos-ventura-)
  - [Monterey](https://github.com/yusufklncc/Hackintosh-for-All-Computers#macos-monterey)
  - [Big Sur](https://github.com/yusufklncc/Hackintosh-for-All-Computers#macos-big-sur)
  - [Catalina](https://github.com/yusufklncc/Hackintosh-for-All-Computers#macos-catalina)
  
### Writing OSX Image

- Unzip the zip file to desktop.
- Download balenaEtcher from this link https://www.balena.io/etcher/
- Open program and click to `Flash from file`
- Select the OSX image `(.raw file)` from the popup window.
- Click to `Select target` and select OSX image.
- Click to `Flash!` and allow app in popup window.
<p align="center">
  <img src="https://user-images.githubusercontent.com/78423442/154849816-0a04602a-9064-4780-9d4e-ed86254b4fea.png">

- When writing is finished, `remove` the USB stick and plug it back in.

### Setting EFI Folder

- When you plug USB back, you can see EFI partition in "My Computer"
- Open EFI partition.
- Delete default files.
- Copy downloaded `EFI` folder to `EFI` partititon.
- Download compatible [AirportItlwm](https://github.com/OpenIntelWireless/itlwm/releases) kext and put it `OC/Kexts` folder.
- Now you can boot from USB.

### Setting BIOS Settings 

  - Before you start, reset your BIOS settings to default.
  - `Disable`
    - Secure Boot
    - Intel Thermal Framework
    
### macOS Installation Steps
- Now let's turn off our computer and boot from USB. Choose the `Install macOS Monterey` (whatever you have) option on OpenCore menu and go to the installation screen.
- <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Installation/macOS%201.png">
- What to do on the following screens:
  - Select language and continue.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Installation/macOS%202.png">
  - Open `Disk Utility` from the menu to prepare our disk.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Installation/macOS%203.png">
  - Select `Show All Devices` from the `Display` option and select the name of our disk and click `Erase`.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Installation/macOS%204.png">
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Installation/macOS%205.png">
  - Rename the disk and erase as `APFS/GUID`.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Installation/macOS%206.png">
  - Now close `Disk Utility` and select `Install macOS Monterey` then next next next.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Installation/macOS%208.png">
  - Select renamed disk and click continue.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Installation/macOS%2010.png">
  - When the installation is finished,  `macOS Installer` option will be selected automatically every boot step until this option is `gone`.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Installation/macOS%2011.png">
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Installation/macOS%2012.png">
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Installation/macOS%2013.png">
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Installation/macOS%2014.png">
  - After last boot, the language selection screen will welcome us. Select language and continue.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Installation/macOS%2015.png">
  - Don't login `iCloud` account and continue. Because we need to set our `serial numbers and ROM for iCloud and iMessage`.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Installation/macOS%2016.png">
  - Now we can see `Desktop`.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Installation/macOS%2017.png">
  
### macOS Post Installation Steps
- Open config file with `Text Edit`.
  - Search `HideAuxiliary` and change `false` value to `true`.
  - Search `SecureBootModel` and change `Disabled` value to `Default`.
  - Search `boot-args` and delete `-v debug=0x100 keepsyms=1` arguments.
- Now we have to set our serial numbers and ROM value.
  - Download [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS/archive/refs/heads/master.zip) and open .command file. If program asks `Download Python` download it. After that select option 3.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/GenSMBIOS/GenSMBIOS%201.png">
  - Now list 5 SMBIOS first.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/GenSMBIOS/GenSMBIOS%202.png">
  - Select and copy first Serial.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/GenSMBIOS/GenSMBIOS%203.png">
  - Go [check](https://checkcoverage.apple.com/) serial number. Your serial should be like this. If not, try second serial.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/GenSMBIOS/Check%20Serial.png">
  - Search MacBookPro15,3 and replace `Serial > SystemSerialNumber, Board Serial > MLB and SmUUID > SystemUUID` values. Now we will set our ROM value.
  - Go `System Setting > Netwotk > Ethernet > Details > Hardware`. If our MAC adress is `54:1A:AF:43:70:CA` remove `:` characters = `541AAF4370CA`. Convert it to [Base64](https://base64.guru/converter/encode/hex). 
  - Now we have `VBqvQ3DK`. Replace this with ROM value and save config file.
  - Restart computer and press `Space` key on OpenCore menu. Then enter `ResetNVRAM`. After that BIOS settings may change. Check it and boot macOS.
  - Now you can login iCloud, iMessage or other apple services and you can use macOS.
  
## Credits
 - [Dortania](https://dortania.github.io) for developing OpenCore.
 - [Apple](https://www.apple.com) for macOS.
 - [Acidanthera](https://github.com/acidanthera) for most of the kexts.
 - [RehabMan](https://github.com/RehabMan) for battery patches.
 - [Sniki](https://github.com/Sniki) for USB kext.
 - Technopat Youtube for Installation images.
 - And anyone else that helped to develop and improve hackintoshing.

<h1 align="center"> Donate - Bağış </h1>
<p align="center">
<a href="https://github.com/yusufklncc/yusufklncc/blob/main/Donate%20-%20Ba%C4%9F%C4%B1%C5%9F.md">
  <img src="https://github.com/yusufklncc/yusufklncc/blob/main/Resources/Donate.png" width="300">
