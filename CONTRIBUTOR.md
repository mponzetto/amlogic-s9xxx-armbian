# Armbian contributor list

First of all, I would like to thank [150balbes](https://github.com/150balbes) for his outstanding contributions and a good foundation for using Armbian in the Amlogic box. The [armbian](https://github.com/armbian/build) system compiled here directly uses the latest official source code for real-time compilation, When making dedicated Armbian systems for different boxes, the kernel, scripts, u-boot and other resources made by [flippy](https://github.com/unifreq/openwrt_packit) for `Amlogic s9xxx openwrt` are used. The development idea of the program comes from the tutorials of authors such as [ebkso](https://www.kflyo.com/howto-compile-armbian-for-n1-box). Thank you for your dedication and sharing, so that we can use the Armbian system in the Amlogic s9xxx box.

Because of these innovations and contributors, we can have the company of the box in the long river of years. We have grown up many years later, but this beautiful memory will always stay deep in the memory for a long time. From now on (This source code repository was created on 2021-09-19), record the achievements of these pioneers and leave them to the new friends who have joined the box circle.

| Innovation and contributors | Record of achievements |
| ---- | ---- |
| [150balbes](https://github.com/150balbes) | He has made outstanding contributions and laid a good foundation for using Armbian in the Amlogic box. |
| [flippy](https://github.com/unifreq) | Developed many Armbian and OpenWrt systems, provided s905d-s922x and many other SOC system boot and firmware production solutions, shared abundant resources and tutorials. The [u-boot](build-armbian/amlogic-u-boot), [dtb](build-armbian/amlogic-dtb), [kernel](https://github.com/ophub/kernel/tree/main/pub/stable), [script](build-armbian/common-files/files/usr/sbin) etc. used on this site all fully adopted his results, and he opened the door to the world of Armbian and OpenWrt from the TV box. |
| [NewbieOrange](https://github.com/NewbieOrange) | [2021-11-14]. He provided the [meson-gxm-t95z-plus.dtb](https://github.com/ophub/amlogic-s9xxx-armbian/blob/main/build-armbian/amlogic-dtb/meson-gxm-t95z-plus.dtb) file and [usage method](build-armbian/common-files/patches/boot/s912-t95z-plus) of the new device [T95Z-Plus](https://www.tokopedia.com/search?st=product&q=t95z%20plus) in [issues](https://github.com/ophub/amlogic-s9xxx-armbian/issues/22#issuecomment-968260448); Shared the [meson-gxl-s905l2-p281.dtb](build-armbian/amlogic-dtb/meson-gxl-s905l2-p281.dtb) file of s905l2 (p281 board) in [pull](https://github.com/ophub/amlogic-s9xxx-armbian/pull/29). |
| [pulpoff](https://github.com/pulpoff) | [2021-11-24]. He shared how to adjust [dtb freq](https://github.com/armbian/build/commit/d0831a7ce191759011d8a0f23019acebc2348149) and add new [display resolution](https://github.com/tobetter/linux/commit/248da29964751908c36e2c5558385ec09aed87ad) in [issues](https://github.com/ophub/amlogic-s9xxx-armbian/issues/31#issuecomment-974982500), and provided test firmware [download](https://vp5.net/king/); In [issues](https://github.com/ophub/amlogic-s9xxx-armbian/issues/36), the test method for `supporting sound` is shared; In [issues](https://github.com/ophub/amlogic-s9xxx-armbian/issues/34), the test method for `enabling Bluetooth` is shared. |
| [flymike](https://github.com/flymike) | [2021-12-28]. He shared the available `meson-gxbb-vega-s95-telos.dtb` and `u-boot-s905.bin` of the `Beelink-Mini-MX 2G` `s905` box in [issues](https://github.com/ophub/amlogic-s9xxx-armbian/issues/57) |
| [martinlanger90](https://github.com/martinlanger90) | [2022-01-01]. He tested and shared the `MECOOL-KI-Pro 2G/16G` `s905d` box using armbian system in [issues](https://github.com/ophub/amlogic-s9xxx-armbian/issues/59). The available dtb is `meson-gxl-s905d-mecool-ki-pro.dtb`, u-boot is `u-boot-p201.bin`, and it can be used in `5.4`, `5.10`, and `5.15` kernels. |
| [ErikPelli](https://github.com/ErikPelli) | [2022-01-14]. He reported in [issues](https://github.com/ophub/amlogic-s9xxx-armbian/issues/72#issuecomment-1013071513) that [Tanix-TX92](http://www.tanix-box.com/project-view/tanix-tx92-android-tv-box-powered-amlogic-s912/) and [VORKE-Z6-Plus](http://www.vorke.com/project/vorke-z6-2/) boxes can use the same configuration as [H96-Pro-Plus](https://www.gearbest.com/tv-box-mini-pc/pp_503486.html), and support writing to `emmc` for use. Supports the use of `mouse` and `keyboard` under the `5.10 kernel`.  |
| [JFLim1](https://github.com/JFLim1) | [2022-01-15]. He shared the available `dtb` and `u-boot` of the `Beelink-GT-King-Pro (Revision A, Serial #SA9HH...)` `s922x` box in [issues](https://github.com/ophub/amlogic-s9xxx-armbian/issues/72#issuecomment-1012127495). After his tests, it was finally determined that the combination of `meson-g12b-gtking-pro.dtb` and `u-boot-gtkingpro-rev-a.bin` could be used. Mouse, keyboard, bluetooth, wireless are normal. |
| [flymike](https://github.com/flymike) | [2022-01-16]. After his test in [issues](https://github.com/ophub/amlogic-s9xxx-armbian/issues/79), in the `MECOOL-KM3-4G` `s905x2` box, the combination of `meson-g12a-sei510.dtb` and `u-boot-x96max.bin` can be used normally, supporting the `5.10 kernel`. Network, bluetooth, wireless are normal. |
| [JFLim1](https://github.com/JFLim1) | [2022-01-18]. After his test in [issues](https://github.com/ophub/amlogic-s9xxx-armbian/issues/81), He provided a solution to the `black screen` of the `gtking-pro-rev-a` box by disabling the `/etc/udev/rules.d/hdmi.rules` file. |


