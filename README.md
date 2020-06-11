# Opencore Gigabyte z390 Gaming X i5 9600kf Rx 5500 xt Build

My EFI With OpenCore 5.9.0 Catalina 10.15.5

**In maintenance**

## Copy Info

**If you want to use this efi, you need set you PlatformInfo to config.plist**

## Configuration

### OpenCore

- OpenCore 5.9.0

### Hardware

|                    |            Type             |
| :----------------: | :-------------------------: |
|    Montherboard    |   Gigabyte Z390 Gaming X    |
|        CPU         |          I5-9600KF          |
| AMD Graphics Card  |    Sapphire RX5500 XT 8G    |
|        RAM         |      16GB 3200MHz DDR4      |
| Solid State Drives | Western Digital SN750 500GB |
| Wifi & Bluetooth   |  BCM94360CD                 |

### Operating System

macOS Catalina 10.15.5

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

## Updates
- 20200611: update opencore to 5.9.0 from 5.8.0 and macos to 10.15.5 from 10.15.4
- 20200515: update opencore to 5.8.0 from 5.7.0 and add wifi and bluetooth
- 20200408: update opencore to 5.7.0 from 5.6.0
- 20200327: update opencore to 5.6.0 from 5.5.0 and macos to 10.15.4 from 10.15.3
- 20200204: unlock cfg lock

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

- Tonyformac
- 黑果小兵 https://blog.daliansky.net/
- XJN'Blog https://blog.xjn819.com/
- [Ionizing/Hackintosh-z390-9600KF-rx590](https://github.com/Ionizing/Hackintosh-z390-9600KF-rx590)
