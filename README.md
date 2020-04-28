Device tree for Xiaomi Redmi 4 Prime (_markw_)
=====================================================


## How to build

1. Set up the build environment following instructions from [here](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni/blob/twrp-9.0/README.md#getting-started)
2. In the root folder of cloned repo you need to clone the device tree:
```bash
git clone https://github.com/SHRP-Devices/device_xiaomi_markw_shrp.git device/xiaomi/markw
```
3. To build:
```bash
export ALLOW_MISSING_DEPENDENCIES=true && . build/envsetup.sh && lunch omni_markw-eng && mka recoveryimage
```


### Phone info

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core 2.0 GHz Cortex-A53
CHIPSET | Qualcomm MSM8953 Snapdragon 625
GPU     | Adreno 506
Memory  | 3 GB
Shipped Android Version | Android 6.0.1 with MIUI 8
Storage | 32 GB
MicroSD | Up to 256 GB (Hybrid)
Battery | 4100 mAh (non-removable)
Dimensions | 141.3 x 69.6 x 8.9 mm
Display | 1080 x 1920 pixels, 5.0" IPS
Rear Camera  | 13.0 MP, Dual LED flash
Front Camera | 5.0 MP
FingerPrint | Yes
Release Date | November 2016

![Xiaomi Redmi 4 Prime](http://cdn2.gsmarena.com/vv/pics/xiaomi/xiaomi-redmi-4-prime-2.jpg "Xiaomi Redmi 4 Prime")
