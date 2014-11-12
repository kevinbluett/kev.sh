---
layout: post-small-feature
permalink: /ble-devices/index.html
title: BLE Devices Nov '14
description: The speed at which the BLE device market is growing is almost ridiculous. Quite a few of the below devices were not even available a month ago! Here we attempt review of cost and information on the chipsets used. 
tags: [about, Jekyll, theme, responsive]
image:
  feature: water.jpg
---

The purpose of this page is not to provide a complete and comprehensive list of all BLE and BLE compatible devices, but to explore the hardware behind a majority for the purposes of my final year project.

There are quite a lot of different BLE devices being both developed and currently released. AisleLabs has a comprehensive list of primed and ready BLE devices [here](http://www.aislelabs.com/reports/beacon-guide/#conc).

### Chipsets

The BLE device market can be condensed down to 4 different chips

1. **Nordic Semiconductor [nRF51822 SoC](https://www.nordicsemi.com/eng/Products/Bluetooth-Smart-Bluetooth-low-energy/nRF51822)**
   * Single chip, 2.4 GHz multi-protocol device
   * 32-bit ARM Cortex M0 CPU core
   * 256kB/128kB flash + 32kB/16kB RAM
2. **Texas Instruments [TI CC2540](http://www.ti.com/product/cc2540&DCMP=LowPowerRFICs+Other&HQS=Other+OT+cc2540)**
   * 8051 MCU (8 or 16 bit)
   * In-System-Programmable Flash, 128 KB or 256 KB
   * 8-KB SRAM
3. **Bluegiga [Bluegiga BLE113](https://www.bluegiga.com/en-US/products/bluetooth-4.0-modules/ble113-bluetooth--smart-module/)** (suspiciously similar to the TI CC2540?)
   * 8051 microcontroller
   * 8kB RAM 
   * 128kB or 256kB Flash
4. Gimbal proprietary chip, further information is currently unknown
   * Not much is known about the chipset

### Primed and Ready BLE Devices

| Title of Device | Manufacturer | CPU | Battery | Available | Pricing | Notes |
|--- |--- |--- |--- |--- |--- |--- |
| Estimote Sticker | Estimote | [Cortex M0 / nRF51822 SoC](https://www.nordicsemi.com/eng/Products/Bluetooth-Smart-Bluetooth-low-energy/nRF51822) | Integrated Battery | Autumn 2014 (Delayed) | $10 (each)
| Estimote Tag | Estimote 	|  [Cortex M0 / nRF51822 SoC](https://www.nordicsemi.com/eng/Products/Bluetooth-Smart-Bluetooth-low-energy/nRF51822) | 620 mAh CR2450 (Not replaceable) | Yes | $33 (each)
| Bleu Station Beacons |  Twocanoes	| N/A | USB Power | Yes | $83 (each) |
| Redbeacon |  Twocanoes	| N/A | USB Power | Yes | $83 (each) | 
| [Bleep Beacon](http://getbleep.com/#smart-spaces) | Rainmaker Labs | ?? | Battery ?? | Yes | $33 (each) 
| [Gimbal](http://www.gimbal.com/) | Qualcomm | N/A | 240mAh  | No | - | Looks a little while out
| [Particle](https://kstechnologies.com/shop/particle/) | KStechnologies | [Cortex M0 / nRF51822 SoC](https://www.nordicsemi.com/eng/Products/Bluetooth-Smart-Bluetooth-low-energy/nRF51822) | 240mAh CR2032   | Yes | $40 | 
| [Radbeacon Tag](http://store.radiusnetworks.com/collections/all/products/radbeacon-tag-1) | Radius Networks | CPU | CR2032 coin-cell battery (replaceable) | Yes | $39
| [IKBS 105 beacons](http://ibeacon.accent-systems.com/) | Accent Systems | [TI CC2540](http://www.ti.com/product/cc2540&DCMP=LowPowerRFICs+Other&HQS=Other+OT+cc2540) ?? | 240mAh CR2032 (replaceable) |  Yes | €16 (each) | Accelerometer
| [AprilBeacon 241](http://aprbrother.com/en/product/AprilBeacon%20241s.htm) | April Brother | [TI CC2540](http://www.ti.com/product/cc2540&DCMP=LowPowerRFICs+Other&HQS=Other+OT+cc2540) | 620mAh CR2450 (replaceable) | Yes | $15 | Very small, chip same size as battery
| [BlueBar Beacon](http://bluesensenetworks.com/product/bluebar-beacon/) | BlueSense Networks (UK) | [Bluegiga BLE113](https://www.bluegiga.com/en-US/products/bluetooth-4.0-modules/ble113-bluetooth--smart-module/) | 620mAh CR2450 (replaceable) | Yes | £20.99 | Long range extender available, with it indoor range 200m, line of sight 450m
| [Glimworm](http://glimwormbeacons.com/) | Gilmworm | [TI CC2540](http://www.ti.com/product/cc2540&DCMP=LowPowerRFICs+Other&HQS=Other+OT+cc2540) ?? | 620mAh CR2450 (replaceable) | Yes | €24.50 |
| [kontact.io](http://kontakt.io/our-technology/technical-specification/) | kontact.io | [Cortex M0 / nRF51822 SoC](https://www.nordicsemi.com/eng/Products/Bluetooth-Smart-Bluetooth-low-energy/nRF51822) | 1000 mAh CR2477 (replaceable) | N/A | N/A | 
| [MineW](www.alibaba.com/product-detail/iBeacon-based-on-CC2541-module-with_1483638858.html) | Shenzhen Minew Technologies | [TI CC2540](http://www.ti.com/product/cc2540&DCMP=LowPowerRFICs+Other&HQS=Other+OT+cc2540) | 1000mAH CR2477 (replaceable) | Yes | $8 |
| [Recco](http://reco2.me/reco/) | Perples, Inc / LG | [Cortex M0 / nRF51822 SoC](https://www.nordicsemi.com/eng/Products/Bluetooth-Smart-Bluetooth-low-energy/nRF51822) | 620mAh CR2450 | Yes | $30 | They're gorgeous! 
| [Model X](https://roximity.com/model-x/) | Roximity | [Cortex M0 / nRF51822 SoC](https://www.nordicsemi.com/eng/Products/Bluetooth-Smart-Bluetooth-low-energy/nRF51822) | 240mAh CR2032 | Yes | $66 | Seems very business focused 
| [Sensorberg](http://www.sensorberg.com/en/#shopify-store) | Sensorberg | [TI CC2540](http://www.ti.com/product/cc2540&DCMP=LowPowerRFICs+Other&HQS=Other+OT+cc2540) | 620 mAh CR2450 | Yes | €30 | Has online platform & SDK 
| [SensorTag](http://www.ti.com/ww/en/wireless_connectivity/sensortag/index.shtml?DCMP=sensortag&HQS=sensortag-bn) | Texas Instruments | [TI CC2540](http://www.ti.com/product/cc2540&DCMP=LowPowerRFICs+Other&HQS=Other+OT+cc2540) | 240 mAh CR2032 | Yes | $25 | Lots of integrated sensors
| [Tōd](http://www.todhq.com/index.html) | Tōdally | [Bluegiga BLE113](https://www.bluegiga.com/en-US/products/bluetooth-4.0-modules/ble113-bluetooth--smart-module/) | 240mAh CR2032 | Yes | $40
| [Gelo](http://www.getgelo.com/beacons/) | Gelo Inc. | Unknown | 2xAAA ~1000mAh | Yes | $35 | Works in all weather conditions 
| [Airfy Beacon](https://www.kickstarter.com/projects/261147844/airfy-beacon-imagination-meets-smart-home-automati/comments) | Airfy | Unknown | Unknown | No | - | Currently in kickstarter

### BLE Chips/Shields

| Title of Device | Manufacturer | CPU | Available | Pricing | SDK(s) | Notes |
|--- |--- |--- |--- |--- |--- |--- |
| [BLE Nano](http://redbearlab.com/blenano/) | Redbear Labs	| [ARM Cortex M0](http://www.arm.com/products/processors/cortex-m/cortex-m0.php) | Yes | $38 (Incl. USB Board) | [Multiple](http://redbearlab.com/blenano/#programming) | USB Board available, board is [Nordic nRF51822 SoC](https://www.nordicsemi.com/eng/Products/Bluetooth-Smart-Bluetooth-low-energy/nRF51822)
| [Blend Micro](http://redbearlab.com/blendmicro/) |  Redbear Labs	| [Atmel ATmega32U4](http://www.atmel.com/devices/atmega32u4.aspx) | No | N/A | [Nordic Arduino SDK](https://devzone.nordicsemi.com/arduino/) | UART for compatibility to Raspiberry Pi, Arduino etc..
| [Blend](http://redbearlab.com/blend/) | Redbear Labs | [Atmel ATmega32U4](http://www.atmel.com/devices/atmega32u4.aspx) | No | N/A | [Nordic Arduino SDK](https://devzone.nordicsemi.com/arduino/) | UART for compatibility to Raspiberry Pi, Arduino etc..
| [BLE Shield](http://redbearlab.com/bleshield/) | Redbear Labs | Slave Operation | Yes | $23.66 | [Nordic Arduino SDK](https://devzone.nordicsemi.com/arduino/) | 
| [BLE Mini](http://redbearlab.com/blemini/) | Redbear Labs | [TI CC2540](http://www.ti.com/product/cc2540&DCMP=LowPowerRFICs+Other&HQS=Other+OT+cc2540) | Yes | $23.66 |  | Broken link to SDK
| [BLEduino](http://bleduino.cc/) | Kytelabs | [Atmel ATmega32U4](http://www.atmel.com/devices/atmega32u4.aspx) | No | N/A | - | Kickstarter active

### Programmable BLE Devices

| Title of Device | Manufacturer | CPU | Available | Pricing | SDK(s) | Notes |
|--- |--- |--- |--- |--- |--- |--- |
| [LightBlue Bean](https://punchthrough.com/bean/) | Punch Through Design | [TI CC2540](http://www.ti.com/product/cc2540&DCMP=LowPowerRFICs+Other&HQS=Other+OT+cc2540) | Yes | $28.50 (each) | Arduino | 
| [Edison](http://www.makershed.com/products/intel-edison-breakout-board-kit) | Intel | [Atom Slivermont 22nm](https://software.intel.com/en-us/android/articles/introducing-4th-generation-intel-atom-processor-baytrail-to-android-developers) | Yes | $75 | Arduino | 

### Unreleased/Vaporware BLE Devices
* [Wearpoint](http://wearpoint.com/)