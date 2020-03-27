# Opencore Gigabyte z390 Gaming X i5 9600kf Rx 5500 xt Build

My EFI With OpenCore 5.6.0 Catalina 10.15.4

**In maintenance**

## Copy Info

**If you want to use this efi, you need set you PlatformInfo to config.plist**

## Configuration

### OpenCore

- OpenCore 5.6.0

### Hardware

|                    |            Type             |
| :----------------: | :-------------------------: |
|    Montherboard    |   Gigabyte Z390 Gaming X    |
|        CPU         |          I5-9600KF          |
| AMD Graphics Card  |    Sapphire RX5500 XT 8G    |
|        RAM         |      16GB 3200MHz DDR4      |
| Solid State Drives | Western Digital SN750 500GB |

### Operating System

macOS Catalina 10.15.4

### BIOS Version

- F8

## Will Workd

- Sleep
- 4K Hardware Speed Up
- iMessage
- App Store
- USB Ports
- Audio Card
- NVRAM
- CFG Unlock

## Current Issues

- No Bluetooth & Wi-Fi device

## Updates
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
