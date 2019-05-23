# RK322x

This is a SoC device for RK322x

**Build**

* `PROJECT=Rockchip DEVICE=RK322x ARCH=arm UBOOT_SYSTEM=rk3229-a95rx1 make image`
* `PROJECT=Rockchip DEVICE=RK322x ARCH=arm UBOOT_SYSTEM=rk3229-hk1mini make image`
* `PROJECT=Rockchip DEVICE=RK322x ARCH=arm UBOOT_SYSTEM=rk3229-d88 make image`
* `PROJECT=Rockchip DEVICE=RK322x ARCH=arm UBOOT_SYSTEM=rk3229-v884k make image`
* `PROJECT=Rockchip DEVICE=RK322x ARCH=arm UBOOT_SYSTEM=rk3229-v88mars make image`

**How to use on an Android device**
- Flash image to a sd-card
- Insert sd-card into the device
- Plug in power and LibreELEC should boot instead of Android
- Remove sd-card from device to boot into Android
