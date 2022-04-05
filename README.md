# clone

# Hals


```
rm -rf hardware/qcom-caf/sm8250/display 

git clone https://github.com/ArrowOS/android_hardware_qcom_display.git -b arrow-12.0-caf-sm8250 hardware/qcom-caf/sm8250/display 

rm -rf hardware/qcom-caf/sm8250/media 

git clone https://github.com/ArrowOS/android_hardware_qcom_media.git -b arrow-12.0-caf-sm8250 hardware/qcom-caf/sm8250/media 

rm -rf hardware/qcom-caf/sm8250/audio 

git clone https://github.com/ArrowOS/android_hardware_qcom_audio.git -b arrow-12.0-caf-sm8250 hardware/qcom-caf/sm8250/audio

```


# Trees

```

git clone https://github.com/aliothtrees/device_xiaomi_alioth -b corvus device/xiaomi/alioth

git clone https://github.com/aliothtrees/device_xiaomi_sm8250 -b main device/xiaomi/sm8250-common

git clone https://github.com/aliothtrees/vendor_xiaomi_alioth -b bliss vendor/xiaomi/alioth

git clone https://github.com/aliothtrees/vendor_xiaomi_sm8250-common -b bliss vendor/xiaomi/sm8250-common

rm -rf packages/resources/devicesettings

git clone https://github.com/aliothtrees/packages_resources_devicesettings -b snow packages/resources/devicesettings

```
# Proton

``` 
git clone --depth=1 https://github.com/kdrag0n/proton-clang.git prebuilts/clang/host/linux-x86/proton-clang

```
# GCC

```

git clone --depth=1 https://gitlab.com/arrowos-project/android_prebuilts_clang_host_linux-x86_clang-r437112b -b master prebuilts/clang/host/linux-x86/clang-r437112b

```
