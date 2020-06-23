# omni_umidigi_power_3
# TWRP device tree for Umidigi Power 3 (Power_3)

## About Device

![Power_3](https://www.umidigi.com/new/Images/power3/overview/1-2.png)

### Specifications


Component Type | Details
--------------:|:-------
Models | Power 3 (Power_3),  (Power_3.E)
CPU     | MediaTek, Helio P60, 4xCortex-A73, 2.0GHz & 4xCortex-A53, 2.0GHz
Chipset | MT6771 (12 nm)
GPU     | ARM Mali G72 MP3, up to 800MHz
architecture | aarch64 (64 bit)
Memory  | 4 GB LPDDR4X Dual Channel
Shipped OS | Vanilla Android 10
Storage | 64 (expandable storage up to 256GB (VFAT))
Battery | Non-removable Li-Ion 6150 mAh battery
Height | 162.1 mm
Width | 77.2 mm
Thickness | 10.3 mm
Weight | 218 g (with battery)
Display | 6.53" FHD+ FullView with 4.50mm in-screen camera
Aspect Ratio | 19.5 : 9
Screen To Body Ratio | ~83.46%
Pixel density | 395 ppi (480 dpi)
Screen resolution | 1080 x 2340 pixels
Protection | None
Quick charging | Yes, 18W Charge & 10W Reverse Charge
Wifi | IEEE802.11 a/b/g/n/ac with support for 5G Wi-Fi Signal / Wi-Fi Direct / Supports Wi-Fi Display
Bluetooth | 4.2, A2DP, LE
GPS | GPS (& A-GPS), Glonass, Galileo, BeiDou
USB | Type-C, OTG Support
Body Build | Front glass, Matte Finish (Back)
Colours | Space Grey, Mightnight Green, Red
Network support | Dual SIM, Dual Standby (4G + support 4G VoLTE in both slots simultaneously)
Card | Dual Nano-SIM
SIM size | SIM1: Nano, SIM2: Nano
Sensors | Proximity Sensor, Ambient Light Sensor, Accelerometer, Gyroscope, Electronic Compass, Rear-mounted Fingerprint Sensor

Primary Camera | AI Front Camera | Ultra Wide Lens | Macro Lens | Depth Camera
----------------:|:---------------:|:---------------:|:----------:|:------------
48MP primary camera, 1/2" image sensor, 1.6μm 4-in-1 super pixel, F/1.79 aperture, 6-element lens | 16 MP
PDAF Fast Focusing | f/2.0 Aperture | Slo-Mo (90fps / 720p)
f/1.8 Aperture | 1.12μm Pixels
5P Lens | AI Beautification
Nightscape | HDR
Hybrid HDR | AI Beautification
Ultra HD | AI Facial Unlock
Chroma Boost
Portrait Mode


Network | Bands
-------:|:-----
2G | GSM 1900 / 1800 / 900 / 850 MHz
3G | UMTS 2100 / 1900 / 900 / 850 MHz
3G | WCDMA: 850 / 900 / 2100MHz
3G Speed | HSDPA 42 Mbit/s / HSUPA 11 Mbit/s
4G | TD-LTE: Bands 38 / 40 / 41 (2535-2655MHz)
4G | FDD-LTE: Bands 1 / 3 / 5 / 8
GPRS | Available
EDGE | Available
HSPA | Available

Tests | Results
-----:|:-------
Performance | [Basemark OS II: 2104 / Basemark OS II 2.0: 2020 Basemark X: 19157](https://www.gsmarena.com/benchmark-test.php3?idPhone=9558#show)
Display | Contrast ratio: 1464:1 (nominal), 2.918 (sunlight)
Camera | Photo / Video
Loudspeaker | Voice 66dB / Noise 71dB / Ring 81dB
Audio quality | Noise -93.5dB / Crosstalk -91.6dB
Battery life | Endurance rating 108h

_Note: Above test results may(not) vary._

**This device tree can be used to build twrp for Realme RMX1821 (Realme 3)**

## Build Instructions
```sh
export ALLOW_MISSING_DEPENDENCIES=true
source build/envsetup.sh
lunch omni_RMX1821-eng
mka recoveryimage
```
