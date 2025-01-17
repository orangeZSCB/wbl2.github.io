---
title: Polaris OS 模拟器
tags: 软件
---

关于 Windows Polaris OS 的介绍详见 [BetaWiki](https://betawiki.net/wiki/Windows_Polaris_OS)。<br>
<!--more-->
Polaris OS 是 Windows Core OS (简称 WCOS) 的取消变体，它和 Andromeda OS 一起取消后变成了 Windows 10X。它只泄露了一个版本，但是缺少大量 shell 文件，导致开机后黑屏。它是 ARM32 架构的，因此我们可以用 QEMU WinRT 版本进行模拟。我顺便做了一个模拟器，用 Inno Setup 打包了安装程序，安装包大小 381.2 MB，安装完成后大小占 1.44 GB。

### 图片

有时间再上传吧

### 更新日志

- v1.0 2023/5/13<br>添加模拟器启动器 Emulator.exe，添加少量依赖文件，添加虚拟磁盘，用 Inno Setup 6.2.2 打包。
- v1.1 (未来版本)<br>预计添加数字签名，减少安装占用内存，添加安装程序语言，重新安装系统。
- v1.2 (未来版本)<br>预计添加 Help.chm 帮助文件，重新设计 Emulator.exe。