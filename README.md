# Hackintosh Configuration for Gigabyte Aero 15W
#### Don't forget to star this project if you like it!
#### *FORK* the project to your own repository and clone it to your machine to make changes.
#### ACPI files are unique, so I strongly recommend you configure your own DSDT when your build is stable.
#### *Current Clover Version of the Project: 4558*
#### *Current macOS Version of the Project: 10.13.5*

## Update
* [20180721] Released a new [RELEASE](https://github.com/Errrneist/Hackintosh-Aero-15W/releases/tag/v10.13.5-fix3) fixing the ethernet. All users are suggested to upgrade to this version.

## Warning
* [WARNING] DO NOT USE FILEVAULT DURING INSTALLATION!!! 100% DISK BREAK AFTER REBOOT GUARANTEED.

## Introduction
#### This EFI configursation is capable for installing too. Replace the EFI folder in the Installation USB.
#### If you want to download the EFI files to try your luck, you can check out the [Configuration Release](https://github.com/Errrneist/Hackintosh-Aero-15W/releases).
#### Or, if you are interested in the theme I used, check it out over here: [Minimalism](https://github.com/Errrneist/Hackintosh-Theme-Minimalism).
#### Or, if you want to see how it looks like in System Information, you can check it out here: [SystemInfo](https://github.com/Errrneist/Hackintosh-Aero-15W/blob/master/SystemInfo.txt).

## Announcements 
* Links below in the *Quick Link* section will navigate you to different macOS versions.
* If you cannot mount EFI via [Clover Configurator](https://mackie100projects.altervista.org/download-clover-configurator/), then here is a *[Guide for mounting EFI using TERMINAL](https://github.com/Errrneist/Hackintosh-Aero-15W/blob/master/Mount%20EFI%20on%20macOS.pdf).*
* macOS 10.14 Mojave is coming soon! The official release is this fall. Super excited! Can't wait to see it happen!
* Therefore, it is unlikely that I will support macOS 10.13.6. Instead, I will add macOS 10.14 Mojave support in the future.
* AppleALC is becoming problemsome and periodically not working, so I replaced with the newest VoodooHDA 2.9.1.
* Therefore, the speaker is not working but at least the headphone jack works.
* Please tell me if you solved this problem!

## Main Information
#### Developer: [@Errrneist](https://www.tonymacx86.com/members/errrneist.1550861/)
### Quick Link
* [macOS 10.12.6](https://github.com/Errrneist/Hackintosh-Aero-15W/releases/tag/10.12.6)
* [macOS 10.13.1](https://github.com/Errrneist/Hackintosh-Aero-15W/releases/tag/10.13.1)
* [macOS 10.13.5](https://github.com/Errrneist/Hackintosh-Aero-15W/releases/tag/v10.13.5-fix2)
### Guide Link
* [Link to this post in TonyMacX86](https://www.tonymacx86.com/threads/gigabyte-aero-15-w-hackintosh.245289/#post-1688701)
* [How to install macOS via UniBeast](https://www.tonymacx86.com/threads/unibeast-install-macos-high-sierra-on-any-supported-intel-based-pc.235474/)
* [Patch Laptop DSDT and ACPI Files for Post Installation](https://www.tonymacx86.com/threads/guide-patching-laptop-dsdt-ssdts.152573/)
* [macOS 10.13 High Sirra General Laptop Support](https://www.tonymacx86.com/forums/high-sierra-laptop-support.192/)
* [macOS 10.13 High Sirra Common Problems](https://www.tonymacx86.com/threads/readme-common-problems-in-10-13-high-sierra.233582/)

### Specs
* CPU: Intel Core i7-7700HQ 4C8T @2.8GHz
* GPU: HD630 + NVIDIA GTX 1060 (Disabled)
* <span style="color:red"> Wifi: BCM943602BAED </span>
* RAM: 16GB DDR4 2400MHZ SODIMM
* Screen: 15' FHD 
* SSD1: Liteon SATA SSD 512GB (macOS)
* SSD2: Toshiba NVMe SSD XG3 1TB (Windows)
* SDXC: Samsung EVO Select 128GB (Ubuntu)
* Ethernet: Intel Mausi Ethernet Controller
* BlueTooth: OK
* WebCamera: OK
* Audio: OK(Headphone)
* Microphone: OK
* ~~AppleALC: OK~~
* NVMe Controller: OK
* USB 3.0 bus: OK
* Backlight Control: OK
* Airdrop: OK
 
## Special Thanks
#### Individual
* [RehabMan](https://www.tonymacx86.com/members/rehabman.429483/)
#### Organization
* [TonyMacX86](https://www.tonymacx86.com)
* [PCBeta](http://bbs.pcbeta.com/forum-558-1.html)

### Best, Errrneist.


