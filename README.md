# Hackintosh Configuration for Gigabyte Aero 15W
#### Don't forget to star this project if you like it!
#### *FORK* the project to your own repository and clone it to your machine to make changes.
#### ACPI files are unique, so I strongly recommend you configure your own DSDT when your build is stable.
#### If you want to download the EFI files to try, you can check out the [Configuration Release](https://github.com/Errrneist/Hackintosh-Aero-15W/releases).
#### Or, if you are interested in the theme I used, check it out over here: [Minimalism](https://github.com/Errrneist/Hackintosh-Theme-Minimalism).

## Announcements 
#### *Current Clover Version of the Project: 4558*
#### *Current macOS Version of the Project: 10.13.5*
* Links below in the *Quick Link* section will navigate you to different macOS versions.
* If you cannot mount EFI via [Clover Configurator](https://mackie100projects.altervista.org/download-clover-configurator/), then here is a *[Guide for mounting EFI using TERMINAL](https://github.com/Errrneist/Hackintosh-Aero-15W/blob/master/Mount%20EFI%20on%20macOS.pdf).*
* macOS 10.14 Mojave is coming soon! The official release is this fall. Super excited! Can't wait to see it happen!
* Therefore, it is unlikely that I will support macOS 10.13.6. Instead, I will add macOS 10.14 Mojave support in the future.

## Main Information
#### Developer: [@Errrneist](https://www.tonymacx86.com/members/errrneist.1550861/)
### Quick Link
* [macOS 10.12.6](https://github.com/Errrneist/Hackintosh-Aero-15W/releases/tag/10.12.6)
* [macOS 10.13.1](https://github.com/Errrneist/Hackintosh-Aero-15W/releases/tag/10.13.1)
* [macOS 10.13.5](https://github.com/Errrneist/Hackintosh-Aero-15W/releases/tag/10.13.5)
### Guide Link
* [Link to this post in TonyMacX86](https://www.tonymacx86.com/threads/gigabyte-aero-15-hackintosh-10-13-1.245289/)
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
* Audio: OK
* Microphone: OK
* AppleALC: OK
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

## Full Spec in System Information
Model Name:	MacBook Pro
  Model Identifier:	MacBookPro14,3
  Processor Name:	Intel Core i7
  Processor Speed:	2.81 GHz
  Number of Processors:	1
  Total Number of Cores:	4
  L2 Cache (per Core):	256 KB
  L3 Cache:	6 MB
  Memory:	16 GB
  Boot ROM Version:	MBP143.0175.B00
  SMC Version (system):	2.45f0
  Serial Number (system):	[---NOT SHOWN---]
  Hardware UUID:	[---NOT SHOWN---]
Apple Bluetooth Software Version:	6.0.6f2
  Hardware, Features, and Settings:
  Name:	Hongjun’s MacBook Pro
  Address:	[---NOT SHOWN---]
  Bluetooth Low Energy Supported:	Yes
  Handoff Supported:	Yes
  Instant Hot Spot Supported:	Yes
  Manufacturer:	Broadcom
  Transport:	USB
  Chipset:	20703A1
  Firmware Version:	v5 c4518
  Bluetooth Power:	On
  Discoverable:	Off
  Connectable:	Yes
  Auto Seek Pointing:	On
  Remote wake:	On
  Vendor ID:	0x0A5C
  Product ID:	0x6410
  HCI Version:	4.1 (0x7)
  HCI Revision:	0x11A6
  LMP Version:	4.1 (0x7)
  LMP Subversion:	0x2105
  Device Type (Major):	Computer
  Device Type (Complete):	Mac Portable
  Composite Class Of Device:	0x38010C
  Device Class (Major):	0x01
  Device Class (Minor):	0x03
  Service Class:	0x1C0
  Auto Seek Keyboard:	On
  Services:
  Bluetooth File Transfer:
  Folder other devices can browse:	~/Public
  When receiving items:	Accept all without warning
  State:	Disabled
  Bluetooth File Exchange:
  Folder for accepted items:	~/Downloads
  When other items are accepted:	Save to location
  When receiving items:	Accept all without warning
  State:	Disabled
  Bluetooth Internet Sharing:
  State:	Disabled
  Incoming Serial Ports:
  Bluetooth-Incoming-Port:
  RFCOMM Channel:	3
  Requires Authentication:	No
HD WebCam:
  Model ID:	UVC Camera VendorID_7119 ProductID_11371
  Unique ID:	[---NOT SHOWN---]
Intel HD Graphics 630:
  Chipset Model:	Intel HD Graphics 630
  Type:	GPU
  Bus:	Built-In
  VRAM (Dynamic, Max):	1536 MB
  Vendor:	Intel
  Device ID:	0x1916
  Revision ID:	0x0004
  Metal:	Supported, feature set macOS GPUFamily1 v3
  Displays:
Display:
  Resolution:	1920 x 1080 (1080p FHD - Full High Definition)
  UI Looks like:	1920 x 1080
  Framebuffer Depth:	24-Bit Color (ARGB8888)
  Main Display:	Yes
  Mirror:	Off
  Online:	Yes
  Rotation:	Supported
  Automatically Adjust Brightness:	No
  Connection Type:	DisplayPort
Memory Slots:
  ECC:	Disabled
  Upgradeable Memory:	No
BANK 0/DIMM2:
  Size:	16 GB
  Type:	DDR4
  Speed:	2400 MHz
  Status:	OK
  Manufacturer:	Crucial Technology
  Part Number:	CT16G4SFD824A.C16FBD
  Serial Number:	[---NOT SHOWN---]
Apple SSD Controller:
THNSN51T02DU7 NVMe TOSHIBA 1024GB:
  Capacity:	1.02 TB (1,024,209,543,168 bytes)
  TRIM Support:	Yes
  Model:	THNSN51T02DU7 NVMe TOSHIBA 1024GB
  Revision:	57DA4103
  Serial Number:	        [---NOT SHOWN---]
  Link Width:	x4
  Link Speed:	8.0 GT/s
  Detachable Drive:	No
  BSD Name:	disk1
  Partition Map Type:	GPT (GUID Partition Table)
  Removable Media:	No
  Volumes:
EFI:
  Capacity:	629.1 MB (629,144,064 bytes)
  File System:	MS-DOS FAT32
  BSD Name:	disk1s1
  Content:	EFI
  Volume UUID:	[---NOT SHOWN---]
Windows:
  Capacity:	1.02 TB (1,022,625,189,888 bytes)
  Available:	69.5 GB (69,504,200,704 bytes)
  Writable:	Yes
  File System:	Tuxera NTFS
  BSD Name:	disk1s2
  Mount Point:	/Volumes/Windows
  Content:	Microsoft Basic Data
disk1s3:
  Capacity:	946.9 MB (946,864,128 bytes)
  BSD Name:	disk1s3
  Content:	Windows Recovery
Realtek 8168/8101E Gigabit Ethernet:
  Name:	ethernet
  Type:	Ethernet Controller
  Driver Installed:	No
  MSI:	No
  Bus:	PCI
  Slot:	Ethernet
  Vendor ID:	0x10ec
  Device ID:	0x8168
  Subsystem Vendor ID:	0x1458
  Subsystem ID:	0x1650
  Revision ID:	0x0016
  Link Width:	x1
  Link Speed:	2.5 GT/s
Battery Information:
  Model Information:
  Serial Number:	Aero 15-Unknown
  Manufacturer:	GIGABYTE
  Device Name:	Aero 15
  Charge Information:
  The battery’s charge is below the critical level.:	No
  The battery’s charge is below the warning level.:	No
  Charge Remaining (mAh):	6200
  Fully Charged:	Yes
  Charging:	No
  Full Charge Capacity (mAh):	6200
  Battery Installed:	Yes
  Amperage (mA):	0
  Voltage (mV):	16701
System Power Settings:
  AC Power:
  System Sleep Timer (Minutes):	0
  Disk Sleep Timer (Minutes):	0
  Display Sleep Timer (Minutes):	0
  Wake on LAN:	Yes
  AutoPowerOff Delay:	28800
  AutoPowerOff Enabled:	1
  Current Power Source:	Yes
  DarkWakeBackgroundTasks:	0
  Display Sleep Uses Dim:	Yes
  GPUSwitch:	2
  Hibernate Mode:	3
  PrioritizeNetworkReachabilityOverSleep:	0
  Standby Delay:	10800
  Standby Enabled:	1
  TCPKeepAlivePref:	1
  Battery Power:
  System Sleep Timer (Minutes):	1
  Disk Sleep Timer (Minutes):	10
  Display Sleep Timer (Minutes):	2
  AutoPowerOff Delay:	28800
  AutoPowerOff Enabled:	1
  DarkWakeBackgroundTasks:	0
  Display Sleep Uses Dim:	Yes
  GPUSwitch:	2
  Hibernate Mode:	3
  Reduce Brightness:	No
  Standby Delay:	10800
  Standby Enabled:	1
  TCPKeepAlivePref:	1
Hardware Configuration:
  UPS Installed:	No
AC Charger Information:
  Connected:	Yes
  ID:	0x07a1
  Wattage (W):	45
  Family:	0x0085
  Serial Number:	[---NOT SHOWN---]
  Charging:	No
Generic AHCI Controller:

  Vendor:	Generic
  Product:	AHCI Controller
  Link Speed:	6 Gigabit
  Negotiated Link Speed:	6 Gigabit
  Physical Interconnect:	SATA
  Description:	AHCI Version 1.31 Supported
LITEON CV1-8B512:
  Capacity:	512.11 GB (512,110,190,592 bytes)
  Model:	LITEON CV1-8B512                        
  Revision:	G890109 
  Serial Number:	[---NOT SHOWN---]       
  Native Command Queuing:	Yes
  Queue Depth:	32
  Removable Media:	No
  Detachable Drive:	No
  BSD Name:	disk0
  Medium Type:	Solid State
  TRIM Support:	No
  Partition Map Type:	GPT (GUID Partition Table)
  S.M.A.R.T. status:	Verified
  Volumes:
disk0s1:
  Capacity:	209.7 MB (209,715,200 bytes)
  BSD Name:	disk0s1
  Content:	[---NOT SHOWN---]
disk0s2:
  Capacity:	511.9 GB (511,900,434,432 bytes)
  BSD Name:	disk0s2
  Content:	Apple_APFS
USB 3.0 Bus:
  Host Controller Driver:	AppleUSBXHCISPT
  PCI Device ID:	0xa12f 
  PCI Revision ID:	0x0031 
  PCI Vendor ID:	0x8086 



