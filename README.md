# Motorola RAZR V3i (R4441D)

![Motorola RAZR V3i](assets/moto.jpg)

This is a place where I put all motorola related software and settings for self reference

## Software

- RSD Lite 3.8 (via Bottles, see `bottle.yml` for config)
- MMPAGI v0.5 for R4441D

### Bottles Setup

1. Install Bottles
2. Create new bottle: Win64, Application, soda runner
3. Install dependencies: `arial32`, `times32`, `courie32`, `mono`, `gecko`, `dotnet40`
4. Run `software/RSDLite_3.8.msi` inside the bottle
5. Launch via: `bottles-cli run -b "rsd-lite" -e /path/to/drive_c/SDL.exe`

## Notes

- Enter bootloader: turn off the phone -> hold *# then red button.

## Device Info

Model: V3e / V3i EDGE variant (R4441D platform) | Firmware: R4441D_G_02.02.DSR | Flex: GSPSLQAT687UC068 (Latin America) | Hardware: CHUG1549AA |  Bootloader: 0A.30

## Commands

`*#06#` IMEI | `*#9999#` Software version | `*#8888#` Hardware version

### Tools

- [RSD Lite](https://firmware.center/software/Motorola/Flashing/Official/RSD%20Lite/)
- [P2K Easy Tool 3.9](https://archive.org/details/p-2-k-easy-tool)
- [P2K Tools 3](https://firmware.center/software/Motorola/Viewing/P2K%20Tools%203/)

### Reference

- [MMPAGI forum thread](https://forum.motofan.ru/index.php?showtopic=136497)
- [GSMForum R4441D langpacks](https://gsmforum.ru/threads/32190/)
- [R4441D to R479 cross-flash](http://matrax.net/forum/showthread.php?p=628441)
- [Language pack codes](https://a9fm.blogspot.com/2010/01/motorola-language-packs-with.html)
