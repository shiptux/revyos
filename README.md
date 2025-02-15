# RevyOS

## Introduction

[RevyOS](https://github.com/revyos)  is a custom Debian distribution optimized for the XuanTie chip ecosystem, supported and developed by the RevyOS team from the [Ruyi SDK](https://github.com/ruyisdk) team.

RevyOS provides comprehensive adaptation and optimization support for chips such as c906fdv, c910v, and c908. By default, it integrates support for the RVV 1.0 and XThead GCC toolchains. Furthermore, it is equipped with glibc and kernel optimized for the RVV 1.0 instruction set.

Currently, RevyOS meets basic user needs in areas like office tasks, web browsing, and video playback.

Thanks to its customizations and optimizations, RevyOS offers superior performance and an excellent experience on hardware platforms like Lichee RV and Lichee Pi 4A.

## Image Download and Flashing

The user version images of __RevyOS__ are currently updated on the ISCAS (Institute of Software, Chinese Academy of Sciences) open-source mirror. To obtain the latest version of __RevyOS__, visit the [image download](https://mirror.iscas.ac.cn/revyos/extra/images/) directory and choose the corresponding image based on your device.

| Supported Devices | Image Download (Latest Version) | Flashing Tutorial | SD Card Support | Mainline Kernel Support |
| --- | --- | --- | --- | --- |
| Lichee Pi 4A | [20240720](https://mirror.iscas.ac.cn/revyos/extra/images/lpi4a/20240720/) | [Flashing Image](./Image%20flashing/licheepi4a.md) |  |  |
| LicheePi Cluster 4A | [20240720](https://mirror.iscas.ac.cn/revyos/extra/images/lpi4a/) | [Flashing Image](./Image%20flashing/licheepi4a.md)  |  |  |
| LicheeConsole 4A | [20240720](https://mirror.iscas.ac.cn/revyos/extra/images/lcon4a/20240720/) | [Flashing Image](./Image%20flashing/licheeconsole4a.md)  |  |  |
| Lichee Book 4A | [20240720](https://mirror.iscas.ac.cn/revyos/extra/images/laptop4a/) | [Flashing Image](./Image%20flashing/licheebook.md)  |  |  |
| Milk-V Pioneer | [20240716](https://mirror.iscas.ac.cn/revyos/extra/images/meles/20240720/) | [Flashing Image](https://milkv.io/zh/docs/pioneer/getting-started/InstallOS)  |  |  |
| Milk-V Meles | [20240720](https://mirror.iscas.ac.cn/revyos/extra/images/meles/20240720/) | [Flashing Image](https://milkv.io/zh/docs/meles/installation)  |  |  |
| Beagle-Ahead | [20231210](https://mirror.iscas.ac.cn/revyos/extra/images/beagle/20231210/) | [Flashing Image]()  |  |  |
| Huiwei book | [20240617](https://mirror.iscas.ac.cn/revyos/extra/images/huiwei/test/20240617/) | [Flashing Image]()  |  |  |

## Updates and Announcements

After an image version update, we will announce the features and changes supported by the current version. If you wish to view the contents supported by the image, click on [RevyOS Version ChangeLog](https://github.com/ruyisdk/revyos/tree/main/Change%20Log) and select the version you're interested in.

## Issues

If you encounter any issues while using the system, you can [submit an issue](https://github.com/revyos/revyos/issues).

## User Documentation

In this repository, we offer various user guides, including documentation on system building, adaptation, and testing. This comprehensive documentation helps users get acquainted with the system more quickly.

For compile and build documentation: [Click here](https://github.com/ruyisdk/revyos/tree/main/Build)

For adaptation-related documentation: [Click here](https://github.com/ruyisdk/revyos/tree/main/Adaptation)

For testing-related documentation: [Click here](https://github.com/ruyisdk/revyos/tree/main/Test).

For 玄铁曳影1520芯片原型用户手册_CN：[Click here](https://occ-oss-prod.oss-cn-hangzhou.aliyuncs.com/resource//1697208997919/%E7%8E%84%E9%93%81%E6%9B%B3%E5%BD%B11520%E8%8A%AF%E7%89%87%E5%8E%9F%E5%9E%8B%E7%94%A8%E6%88%B7%E6%89%8B%E5%86%8C_CN.zip)

For TH1520 User Manual_EN：[Click here](https://occ-intl-prod.oss-ap-southeast-1.aliyuncs.com/resource//1698839996662/TH1520%20User%20Manual%20(1).zip)

For TH1520 Specifications V1.03: [Click here](https://occ-oss-prod.oss-cn-hangzhou.aliyuncs.com/resource/889768/1698042403122/%E6%9B%B3%E5%BD%B11520%E8%A7%84%E6%A0%BC%E4%B9%A6V1.03.pdf)
