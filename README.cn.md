# RevyOS

## 简介

[RevyOS](https://github.com/orgs/revyos/repositories)是由RuyiSDK团队的RevyOS小队支持开发的一款针对XuanTie芯片生态的Debian优化定制发行版。

__RevyOS__ 围绕玄铁C906、C910、C920、C908等芯片提供了完整而全面的适配和优化支持，默认集成支持玄铁扩展指令集和RVV 1.0的GCC工具链，并搭载使用RVV 1.0指令集优化过的Glibc和Kernel。

目前，__RevyOS__ 在办公、网页浏览、观看视频等方面已经能满足用户的基本使用需求。

基于上述定制和优化的 __RevyOS__，在 Lichee RV，Lichee Pi 4A 等硬件平台上，能够提供优秀的性能和极佳的体验。

## 镜像下载及刷写

__RevyOS__ 的用户版镜像目前在 ISCAS（中国科学院软件研究所） 开源镜像站进行更新。如您想获取 __RevyOS__ 最新版镜像请访问[镜像下载](https://mirror.iscas.ac.cn/revyos/extra/images/)目录，根据所使用设备来获取对应镜像。

| 支持设备 | 镜像下载（最新版本） | 刷写教程 | sd卡支持 | 主线内核支持 |
| --- | --- | --- | --- | --- |
| Lichee Pi 4A | [20240720](https://mirror.iscas.ac.cn/revyos/extra/images/lpi4a/20240720/) | [镜像刷写](./Image%20flashing/licheepi4a.md) |  |  |
| LicheePi Cluster 4A | [20240720](https://mirror.iscas.ac.cn/revyos/extra/images/lpi4a/) | [镜像刷写](./Image%20flashing/licheepi4a.md)  |  |  |
| LicheeConsole 4A | [20240720](https://mirror.iscas.ac.cn/revyos/extra/images/lcon4a/20240720/) | [镜像刷写](./Image%20flashing/licheeconsole4a.md)  |  |  |
| Lichee Book 4A | [20240720](https://mirror.iscas.ac.cn/revyos/extra/images/laptop4a/) | [镜像刷写](./Image%20flashing/licheebook.md)  |  |  |
| Milk-V Pioneer | [20240716](https://mirror.iscas.ac.cn/revyos/extra/images/meles/20240720/) | [镜像刷写](https://milkv.io/zh/docs/pioneer/getting-started/InstallOS)  |  |  |
| Milk-V Meles | [20240720](https://mirror.iscas.ac.cn/revyos/extra/images/meles/20240720/) | [镜像刷写](https://milkv.io/zh/docs/meles/installation)  |  |  |
| Beagle-Ahead | [20231210](https://mirror.iscas.ac.cn/revyos/extra/images/beagle/20231210/) | [镜像刷写]()  |  |  |
| Huiwei book | [20240617](https://mirror.iscas.ac.cn/revyos/extra/images/huiwei/test/20240617/) | [镜像刷写]()  |  |  |

## 更新内容

镜像版本更新后我们会公布当前版本镜像支持内容，如您想查看镜像支持内容请点击[RevyOS版本更新日志](./Change%20Log/)后选择您所需要的版本进行查看。

## issue相关

如果您在使用过程中遇到问题，可以进行[issue申报](https://github.com/revyos/revyos/issues)。

## 用户文档

在本仓库中，我们拥有相关的使用构建与适配文档以及测试文档方便让用户对部分内容进行参考，完善的文档支持加快了用户对于系统的上手时间。

编译与构建相关文档：[点击此处](./Build/)

适配相关文档：[点击此处](./Adaptation/)

测试相关文档：[点击此处](./Test/)

玄铁曳影1520芯片原型用户手册_CN：[点击此处](https://occ-oss-prod.oss-cn-hangzhou.aliyuncs.com/resource//1697208997919/%E7%8E%84%E9%93%81%E6%9B%B3%E5%BD%B11520%E8%8A%AF%E7%89%87%E5%8E%9F%E5%9E%8B%E7%94%A8%E6%88%B7%E6%89%8B%E5%86%8C_CN.zip)

TH1520 User Manual_EN：[点击此处](https://occ-intl-prod.oss-ap-southeast-1.aliyuncs.com/resource//1698839996662/TH1520%20User%20Manual%20(1).zip)

曳影1520规格书V1.03: [点击此处](https://occ-oss-prod.oss-cn-hangzhou.aliyuncs.com/resource/889768/1698042403122/%E6%9B%B3%E5%BD%B11520%E8%A7%84%E6%A0%BC%E4%B9%A6V1.03.pdf)
