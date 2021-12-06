## PBRP device tree for the Samsung M215F.

## How to compile

1. Set up the build environment following instructions from [here](https://github.com/PitchBlackRecoveryProject/manifest_pb)
2. Clone the device tree in the root of PBRP source:
```
git clone https://github.com/naz664/device_samsung_m21.git device/samsung/m21
```
3. To build:
```
export ALLOW_MISSING_DEPENDENCIES=true && . build/envsetup.sh && lunch omni_m21-eng && mka recoveryimage -j$(nproc)
```



