# GB-Z390-Gaming-X-OpenCore-RX6600XT-i9-9900K

![Screenshot 2022-12-19 at 00 12 11](https://user-images.githubusercontent.com/29648161/208308319-a9e92507-e720-4738-bb46-be005b0bf01d.png)

## Specs:
```
Motherboard: Gigabyte Z390 Gaming X
Processor: Intel i9-9900K @ 5Ghz
OpenCore: 0.8.7
SMBIOS: 19.1
Monitor: Dual 4k Monitor
RAM: G.SKILL RIPJAWS (8G + 8G + 16G + 16G) 48GB 3200 DDR4
HDD: SSD 4T Cosair MX500
OSX: OSX Ventura 13.0.1
GFX: XFX RX6600XT QUICKSILVER 308
WIFI/BT: BCM94360CD

USB has been set to 15 ports.
IGP has been set to 1.2Ghz igfxrpsc = 1 See WhateverGreen
```
## ISSUES/FIXES:
```
1. Make XFX RX6600XT boot correctly. fixed
2. wake from sleep needs two clicks to turn on monitor. Will hang occasionally. Fixed
3. Bluetooth does not work well. Range is very limited even with Apple magic Mouse and Magic Keyboard.
```

## How to use:
```
0. Make sure BIOS is setup correctly (see below)
1. Download whole EFI and copy to your EFI partition
2. Update MLB, ROM, UUID, Serial to YOUR OWN. You can use OpenCore Configurator to generate for you.
3. Save and Reboot.
```

![Screenshot 2022-12-19 at 00 45 02](https://user-images.githubusercontent.com/29648161/208309994-a720a068-0814-4c61-828c-0fbf9622579d.png)

## Bios:
```
- IGP Enabled 
- CFG Lock Disabled
- Serial Port Disable
- Advanced Mode > Settings > Above 4G Decoding > Enabled
- Advanced Mode > Settings > USB Configuration > XHCI Hand-off > Enabled
- Advanced Mode > Boot > CSM Support > Disabled
```
optional (if using 9900K processor)
- Overclock to 5Ghz [Tips](https://www.gigabyte.com/FileUpload/Global/multimedia/2/file/525/946.pdf)

