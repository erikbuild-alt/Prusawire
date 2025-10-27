---
layout: default
title: Software Overview
has_children: true
nav_order: 7
---

# Software Overview

## Klipper Configuration Files

The most up–to–date Klipper configuration files for setting up or updating the Prusawire are in our [config repository](https://github.com/Positron3D/prusawire-klipper-config).

## Upgrading the Einsy Rambo to Klipper - Read this

Installing Klipper on the Einsy Rambo board is possible, with extra steps. Follow the guide [published by the awesome folks at MyRigs3D](https://myrigs3d.com/blogs/infos/revive-your-prusa-mk3s-with-klipper-1-5-flash-bootloader)! We recommend Method 2.

**Note:** Some users have reported problems using `avrdude` with the latest Raspberry Pi OS version (bookworm). If you experience error messages from avrdude complaining about gpio ports being busy, please try using the bullseye version of Raspberry Pi OS instead, available as "Raspberry Pi OS (Legacy)" in Raspberry Pi Imager.


## Resources
- [Voron Software Installation Guide](https://docs.vorondesign.com/build/software/) for some good resources on Mainsail (Klipper on Raspberry Pi) and Control Board firmware.
- [Raspberry Pi OS based \| MainsailOS](https://docs-os.mainsail.xyz/getting-started/raspberry-pi-os-based)
- [Welcome to Mainsail \| Mainsail](https://docs.mainsail.xyz/)
- [GitHub - bigtreetech/BIGTREETECH-SKR-mini-E3](https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3)
- [BIGTREETECH-SKR-mini-E3/firmware/V3.0/Klipper at master · bigtreetech/BIGTREETECH-SKR-mini-E3 · GitHub](https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3/tree/master/firmware/V3.0/Klipper)

## Configuration
Start with the [Positron3D Prusawire Configuration](https://github.com/Positron3D/prusawire-klipper-config) settings and profiles.

More detail general instructions are found at [Software Configuration \| Voron Documentation](https://docs.vorondesign.com/build/software/configuration.html).

### Sensorless Homing
If you are running the Einsy board, congrats, you are now done.

For the BTT SKR Mini E3, some further tuning likely needs to happen. Refer to [this guide](https://gist.github.com/clee/9108f7717defce8b1222698f816def0a#finding-the-right-stallguard-threshold) by clee on setting the correct stallguard threshold.
### Input Shaper
Some defaults have been provided, but they are no doubt unsuitable for your exact machine. We recommend installing [ShakeTune](https://github.com/Frix-x/klippain-shaketune) for measuring resonances, and reading the [Klipper guide](https://www.klipper3d.org/Measuring_Resonances.html#max-smoothing) on understanding which value to choose.

**Y Axis Input Shaping**: This requires an external accelerometer (eg LDO Input Shaper) to be mounted to your heated bed.