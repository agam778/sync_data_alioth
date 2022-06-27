# sync_data_alioth

## Device tree (my own)
### alioth Device Tree
```bash
git clone git clone git@github.com:agam778/device_xiaomi_alioth.git device/xiaomi/alioth
```
### common Device Tree
```bash
git clone git@github.com:agam778/device_xiaomi_sm8250-common.git device/xiaomi/sm8250-common
```

## Device Tree (by [@cristianvaz](https://github.com/cristianvaz))
### alioth Device Tree
```bash
git clone git@github.com:cristianvaz/device_xiaomi_alioth.git device/xiaomi/alioth
```
### common Device Tree
```bash
git clone git@github.com:cristianvaz/device_xiaomi_sm8250-common.git device/xiaomi/sm8250-common
```

## Vendor Tree (by [@cristianvaz](https://github.com/cristianvaz))
```bash
git clone git@github.com:cristianvaz/vendor_xiaomi_alioth.git vendor/xiaomi/alioth
git clone git@github.com:cristianvaz/vendor_xiaomi_sm8250-common.git vendor/xiaomi/sm8250-common
```

## Kernels
### InfiniR
```bash
git clone git@github.com:raystef66/InfiniR_kernel_alioth.git -b 12.1-alioth kernel/xiaomi/sm8250
```

### Quantic
```bash
git clone https://github.com/Official-Ayrton990/android_kernel_xiaomi_sm8250.git -b upstreamed-common kernel/xiaomi/sm8250
```

### Immensity by UtsavBalar1231
```bash
git clone git@github.com:UtsavBalar1231/kernel_xiaomi_sm8250.git kernel/xiaomi/sm8250
```

### Immensity fork by VoidUI (supports `sdclang`)
```bash
git clone git@github.com:VoidUI-Devices/kernel_xiaomi_sm8250.git kernel/xiaomi/sm8250
```

### N0kernel
```bash    
git clone git@github.com:EmanuelCN/kernel_xiaomi_sm8250.git -b staging kernel/xiaomi/sm8250
```

## Clangs
### Proton Clang (EOL)
```bash
git clone --depth=1 https://github.com/kdrag0n/proton-clang.git prebuilts/clang/host/linux-x86/proton-clang
```

### AOSP Clang 14
```bash
git clone https://github.com/drkphnx/android_prebuilts_clang_host_linux-x86_clang-r437112.git -b master prebuilts/clang/host/linux-x86/clang-r437112 
```

### SDClang
```bash
git clone https://github.com/VoidUI/prebuilts_clang_host_linux-x86_clang-sdclang -b aosp-12.1 prebuilts/clang/host/linux-x86/clang-sdclang
```

### Neutron Clang 15
```bash
git clone https://gitlab.com/dakkshesh07/neutron-clang prebuilts/clang/host/linux-x86/clang-neutron
```

## Xiaomi Hardware (required to build Xiaomi Parts)
```bash
rm -rf hardware/xiaomi
git clone git@github.com:LineageOS/android_hardware_xiaomi.git -b lineage-19.1 hardware/xiaomi
```

## HALS
```bash
rm -rf hardware/qcom-caf/sm8250/display 
git clone git@github.com:PixelPlusUI-Devices/alioth_hardware_qcom-caf_sm8250_display.git -b snowcone hardware/qcom-caf/sm8250/display 

rm -rf hardware/qcom-caf/sm8250/media 
git clone git@github.com:PixelPlusUI-Devices/alioth_hardware_qcom-caf_sm8250_media.git -b snowcone hardware/qcom-caf/sm8250/media 

rm -rf hardware/qcom-caf/sm8250/audio 
git clone git@github.com:PixelPlusUI-Devices/alioth_hardware_qcom-caf_sm8250_audio.git -b snowcone hardware/qcom-caf/sm8250/audio 
```

## ant-wireless
```bash
rm -rf external/ant-wireless/antradio-library
git clone git@github.com:drkphnx/external_ant-wireless_antradio-library.git -b snowcone external/ant-wireless/antradio-library
```

## NFC (for some roms that doeesn't have kryo 785 support in source nfc package)
```bash
rm -rf vendor/nxp/opensource/commonsys/packages/apps/Nfc
git clone git@github.com:drkphnx/vendor_nxp_opensource_commonsys_packages_apps_Nfc.git -b snowcone vendor/nxp/opensource/commonsys/packages/apps/Nfc
```

## Gcam BSG
```bash
 git clone https://gitlab.com/Alioth-Project/vendor_GcamBSG.git -b twelve vendor/GcamBSG
```
