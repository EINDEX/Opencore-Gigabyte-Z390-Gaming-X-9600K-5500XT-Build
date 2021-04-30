# Opencore Gigabyte z390 Gaming X i5 9600kf Rx 5500 xt Build

My EFI With OpenCore 6.8.0 Big Sur 11.3 (20E232)

**Welcome to raise issue for my efi config**

## Notice

Want to setup this efi on your Hackintosh, Please checking those:

- Set you `PlatformInfo` in `config.plist`
- Disable `USBPorts.ketx` checking [Usb Issues](https://dortania.github.io/OpenCore-Install-Guide/troubleshooting/extended/kernel-issues.html#usb-issues)


## Updates

**In maintenance**
### Update frequency
Will be updated at least every three months

### Update logs
- 20210430: upgrade opencore to 6.8.0 and macos to 11.3 (20E232)
- 20210309: upgrade opencore to 6.7.0 from 6.3.0 and macos to 11.2.3 (20D91) from 11.0.1
- 20201113: upgrade opencore to 6.3.0 from 6.2.0 and macos to 11.0.1 from 10.15.7
- 20201011: upgrade opencore to 6.2.0 from 5.9.0 and macos to 10.15.7 from 10.15.5
- 20200611: upgrade opencore to 5.9.0 from 5.8.0 and macos to 10.15.5 from 10.15.4
- 20200515: upgrade opencore to 5.8.0 from 5.7.0 and add wifi and bluetooth
- 20200408: upgrade opencore to 5.7.0 from 5.6.0
- 20200327: upgrade opencore to 5.6.0 from 5.5.0 and macos to 10.15.4 from 10.15.3
- 20200204: unlock cfg lock

## Configuration

### OpenCore

- [OpenCore](https://github.com/acidanthera/OpenCorePkg) 6.8.0

### Hardware

|                    |            Type             |
| :----------------: | :-------------------------: |
|    Montherboard    |   Gigabyte Z390 Gaming X    |
|        CPU         |          I5-9600KF          |
| AMD Graphics Card  |    Sapphire RX5500 XT 8G    |
|        RAM         |    2 * 16GB 3200MHz DDR4    |
| Solid State Drives | Western Digital SN750 500GB |
| Wifi & Bluetooth   |  BCM94360CD                 |

### Operating System

macOS Big Sur 11.3 (20E232)

### BIOS Version

- F8

## Will Worked

- Sleep
- 4K Hardware Speed Up
- iMessage
- App Store
- USB Ports
- Audio Card
- NVRAM
- CFG Unlock

## Current Issues

- ~~Big Apple logo~~
- SideCar and FCPX can not work beacuse my cpu with F


## Images

![](/img/Xnip2020-02-04_16-16-37.jpg)

![](/img/Xnip2020-02-04_16-15-20.jpg)

## How To Unlock CFG

If you bios version same with me. 'Gigabyte Z390 Gaming X F8'

just open `grub shell` tool input this commend.

```grub
setup_var_c 0x5C1 0x00
```

## Thanks

- OpenCorePkg https://github.com/acidanthera/OpenCorePkg
- Dortania https://dortania.github.io/getting-started/
- Tonyformac
- 黑果小兵 https://blog.daliansky.net/
- XJN'Blog https://blog.xjn819.com/
- [Ionizing/Hackintosh-z390-9600KF-rx590](https://github.com/Ionizing/Hackintosh-z390-9600KF-rx590)

- [Issue #2](https://github.com/EINDEX/Opencore-Gigabyte-z390-Gaming-X-i5-9600kf-Rx-5500-xt-Build/issues/2)