# LKE-programming-language
How to create an "ARMintosh" for Raspberry Pi 4!


Installing LKE Extension on Mac & Linux
```
$ sudo apt get install lke --package --lke2 --lkeapps
```
Creating an Hard Disk for LucuzOS XI 
```
$ sudo lke --emulators qemu --hdd 128G --format "ntfs" -hda -d --cdrom "/Users/youruser/Downloads/LucuzOS 1.0 I.iso" --version --with "DirectX11" --createlucuzosmedia
```
Booting LucuzOS on Qemu using LKE Emulators!
```
qemu install lucuzos1.qcow2 __init__ boot: -d -- __init__
```
Converting OSes from LucuzOS to LKEARM Bootloader for Raspberry Pi 4B and installing macOS 14.4 Sonoma
```
qemu install lucuzos1.qcow2 __init__ boot: -d -- __init__ --convert from __LucuzOS1.qcow2__ to __macOS 14.4 Sonoma__ boot -d with "/Users/youruser/Downloads/Sonoma.iso" convert V2P "USB 3.1"
```
If you don't have V2P install it:

```
$ sudo apt get install v2pqemu
```
