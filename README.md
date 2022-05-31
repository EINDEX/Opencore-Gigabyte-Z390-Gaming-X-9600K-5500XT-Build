# Opencore Gigabyte z390 Gaming X i5 9600K 5500-XT Build

**Stop update anymore, Got a m1 pro chip mac to replace this one.**

## Notice

Want to setup this efi on your Hackintosh, Please checking those:

- Check your CFG Status
- Set you `PlatformInfo` in `config.plist`
- Disable `USBPorts.ketx` checking [Usb Issues](https://dortania.github.io/OpenCore-Install-Guide/troubleshooting/extended/kernel-issues.html#usb-issues)


## Updates

**In maintenance**
### Update frequency
Will be updated at least every 6 months.

## Configuration

### OpenCore

- [OpenCore](https://github.com/acidanthera/OpenCorePkg) 0.7.5

### Hardware

|                    |            Type             |
| :----------------: | :-------------------------: |
|    Montherboard    |   Gigabyte Z390 Gaming X    |
|        CPU         |          I5-9600K           |
| AMD Graphics Card  |    Sapphire RX5500 XT 8G    |
|        RAM         |    2 * 16GB 3200MHz DDR4    |
| Solid State Drives | Western Digital SN750 500GB |
| Wifi & Bluetooth   |  BCM94360CD                 |

### Operating System

macOS Monterey 12.0.1 (21A559)

### BIOS Version

- F8

### Update logs
- 20211108: upgrade opencore to 0.7.5 and macos to 12.0.1 (21A559) and change CPU to 9600K
- 20210922: upgrade opencore to 0.7.3 and macos to 12.0 Beta (21A5506j)
- 20210430: upgrade opencore to 0.6.8 and macos to 11.3 (20E232)
- 20210309: upgrade opencore to 0.6.7 and macos to 11.2.3 (20D91) from 11.0.1
- 20201113: upgrade opencore to 0.6.3 and macos to 11.0.1 from 10.15.7
- 20201011: upgrade opencore to 0.6.2 and macos to 10.15.7 from 10.15.5
- 20200611: upgrade opencore to 0.5.9 and macos to 10.15.5 from 10.15.4
- 20200515: upgrade opencore to 0.5.8 and add wifi and bluetooth
- 20200408: upgrade opencore to 0.5.7
- 20200327: upgrade opencore to 0.5.6 and macos to 10.15.4 from 10.15.3
- 20200204: unlock cfg lock

## Will Worked

- Sleep
- 4K Hardware Speed Up
- iMessage
- App Store
- USB Ports
- Airdorp
- Handoff
- Audio Card
- NVRAM
- CFG Unlock
- FCPX
- SideCar


## How To Unlock CFG

If you bios version same with me. 'Gigabyte Z390 Gaming X F8'

just open `grub shell` tool input this commend.

```grub
setup_var_c 0x5C1 0x00
```


## Reports

### macOS basic infomation
![](/img/BasicInfomation.png)

### CPU Turbo Boost 
![](/img/CPU-Inter-Power-Gadget.png)

### VideoProc
![](/img/VideoProc-report.jpg)

### USB mapping
![](/img/USBPorts-mapping.png)

### Geekbanch

#### CPU
![](/img/CPU-Geekbanch.png)

#### GPU OpenCL
![](/img/GPU-Geekbanch-OpenCL.png)

#### GPU Metal
![](/img/GPU-Geekbanch-Metal.png)


## Thanks

- OpenCorePkg https://github.com/acidanthera/OpenCorePkg
- Dortania https://dortania.github.io/getting-started/
- Tonyformac
- 黑果小兵 https://blog.daliansky.net/
- XJN'Blog https://blog.xjn819.com/
- [Ionizing/Hackintosh-z390-9600KF-rx590](https://github.com/Ionizing/Hackintosh-z390-9600KF-rx590)
- [Issue #2](https://github.com/EINDEX/Opencore-Gigabyte-z390-Gaming-X-i5-9600kf-Rx-5500-xt-Build/issues/2)
