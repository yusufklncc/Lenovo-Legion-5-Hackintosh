<h1 align="center"> macOS on Lenovo Legion 5 15IMH05H </h1>

<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/blob/main/Legion5.png" alt="Legion 5" width="300">
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

# Screenshots 📷

<details>
<summary>Big Sur</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh/blob/main/Big%20Sur.png">
</p>
</details>
 
# Original Hardware  💻

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

# Update History
- ✅ macOS Monterey 12.0.1
- ✅ macOS Big Sur 11.6.1
- ✅ macOS Big Sur 11.0.1

# What's working  💻
Type | Status
:---------|:---------|:----------
Turbo boost and CPU frequency stage |  ✅  
Intel UHD Graphics 630              |  ✅  
Audio Realtek ALC 257            |  ✅  
Realtek Ethernet RTL8111            |  ✅  
Intel Wi-Fi and Bluetooth, Handoff, iMessage...         |  ✅  
USB 3.0 and Type-C (with Port Map)        |  ✅  
Touchpad (14 gestures are working)   |  ✅  
Battery status   |  ✅  
Camera   |  ✅  
S3 Sleep / Wake   |  ✅  
S4 Hibernation / Wake   |  ✅  
Shutdown / Reboot   |  ✅  
Fn shortcut keys   |  ✅  
 
# What's not working  💻
Type | Info | Status
:---------|:---------|:----------
Brightness control | Brightness level is coming from Windows. If you set your brightness %50 in Windows. Your macOS level is %50 | ⚠️
HDMI | Beacuse it connected to RTX2060 | ❌
Airdrop, Sidecar | Beacuse Intel Wi-Fi Doesn't Support | ❌

# What's you have to do  💻
Type | Info | Status
:---------|:---------|:----------
SMBIOS Settings  | With OpenCore Configurator you should definitely set your SMBIOS settings and ROM value because the config does not contain SMBIOS information MacBook Pro 16.4. ROM value is your ethernet MAC address. Be sure your ethernet is en0 in Hackintool. |  ⚠️
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
<a href="https://github.com/yusufklncc/yusufklncc/blob/main/Donate%20-%20Ba%C4%9F%C4%B1%C5%9F.md">
  <img src="https://github.com/yusufklncc/yusufklncc/blob/main/Resources/Donate.png" width="300">
