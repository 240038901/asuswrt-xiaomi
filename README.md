# AsusWRT Xiaomi
This is version of AsusWRT that works with Xiaomi Mi routers, based on MT7621 CPU.

## Supported devices
- Xiaomi MI R3G v1 - use R3G firmware
- Xiaomi MI R3G v2 and R4A - use R4A firmware
- Xiaomi AC2100, Xiaomi Redmi AC2100 - use R2100 firmware for black (cylinder) variant and use RM2100 firmware for white (6 antennas) variant
- Xiaomi R3P, Mi WiFi 4 - not supported now (testers needed)

## How to install
1. Download image from Releases page or build it from source
2. Flash it to a router from stock firmware or bootloader

## Installation from firmware
Please check out the Wiki for this project

## Installation from bootloader or for advanced users
- SPI flash - image needs to be written at 0x180000 offset
- NAND flash - image needs to be written at 0x600000 offset

## How to build image from source
1. cd release/src-ra-5010
2. make model (currently available models are: rt-mir3g, rt-mir4a, rt-rm2100, rt-r2100)

## Missing features
- No dual-wan support

## Important note
- I do not take responsibility for any damages - you do everything on your own risk
