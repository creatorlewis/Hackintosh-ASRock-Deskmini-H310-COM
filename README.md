# Hackintosh : ASRock Deskmini H310/COM



## 适用系统版本

MacOS 10.15.0 Catalina 可以使用官方推送更新为 10.15.1

## 重要发现

今天(1911系统完成了官方推送的 10.15.1 的更新

官方升级成功,由 10.15 升级 为 10.15.1

升级前截图

![10.15.0](https://github.com/creatorlewis/Hackintosh-ASRock-Deskmini-H310-COM/blob/master/Resources/10.15.0.jpg)

升级后截图

![10.15.1](https://github.com/creatorlewis/Hackintosh-ASRock-Deskmini-H310-COM/blob/master/Resources/10.15.1.jpg)



## 检查项

- [x] 官方推送升级正常,完成 10.15.0 升级为 10.15.1

- [x] apple store/TV 账号使用完美
- [x] 睡眠完美
- [x] 开关机完美
- [x] 音频自动转换耳机与显示器音响完美
- [x] usb2.0 & 3.0 完美
- [x] DP、HDMI输出2K显示完美（没有4K显示器，没有测试双显示器输出）VGA不支持
- [x] 蓝牙正常 必须接天线信号才好
- [x] 无线正常 必须接天线信号才好
- [x] 有线网络完美

## 主机配置

|                准系统 | ASRock H310/COM BIOS 4.1 |
| --------------------: | ------------------------ |
|                   CPU | I3-8100                  |
|                  显卡 | 集成显卡 UHD 630         |
|                  内存 | DDR4 8G * 2              |
|             网卡&蓝牙 | BCM94360CS2              |
|                  硬盘 | 东芝 240G sata 固态      |
| M.2转接卡&转接线&天线 | 某宝随手淘               |
|                显示器 | BenQ BL2420PT            |

## 使用方法

1. 按照黑果小兵的介绍一步步安装

2. 安装完成，使用别的电脑挂载硬盘efi分区

3. 拷贝替换同名目录下文件即可

   ###  安装前BIOS 设置

   1. USB Configuration  XHCI Hand-off :  `Enabled`
   2. Onboard HD Audio : ` Enabled`
   3. Security boot : `Disabled`
   4. others :` Default`



## 特别感谢

### [leogitpro](https://github.com/leogitpro)/**[Hackintosh-DeskMini310](https://github.com/leogitpro/Hackintosh-DeskMini310)**

特别感谢这位老哥，CLOVER目录下基本都用的这位老哥的，可以按照这位老哥的指导去驱动BCM94352Z

为了适配蓝牙，激活主板上的usb接针，用clover configuration软件自带的下载了USBinjectall.kext，

同时因为usb3.0的问题也做了一些调整

### [【黑果小兵】macOS Catalina 10.15 19A583 正式版 with Clover 5096原版镜像[双EFI双平台版]](https://blog.daliansky.net/macOS-Catalina-10.15-19A583-Release-version-with-Clover-5093-original-image-Double-EFI-Version.html)

特别感谢黑果小兵的安装镜像及说明，排除硬件问题后，流畅安装无压力

APPLE，BOOT目录下文件均是黑果小兵的

### [解决安装黑苹果macOS Catalina 10.15 Beta1 USB3.0或USB3.1无法使用](https://osx.cx/fix-hackintosh-macos-catalina-10-15-beta1-usb3-0.html)

特别感谢这位老哥的文章帮我解决了usb3.0不能使用的问题









