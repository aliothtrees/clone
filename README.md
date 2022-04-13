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
git clone https://github.com/aliothtrees/dot_device_xiaomi_alioth device/xiaomi/alioth

git clone https://github.com/aliothtrees/dot_vendor_xiaomi_alioth vendor/xiaomi/alioth

rm -rf hardware/xiaomi

git clone https://github.com/aliothtrees/hardware_xiaomi hardware/xiaomi

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
