# LinuxDK

板载资源：

    一个OLED 128x80
    一个麦克风 & 功放可以外接喇叭
    双面不同功能的Type-C接口分别提供USB转串口以及USB-OTG功能
    一个USB-A口用于外接设备
    SD卡插槽
    引出绝大部分IO

板卡成本应该不到50RMB，而且提供了很多资料，很适合用于新手作为入门Linux学习的开发板。

F1C200s基于ARM 9架构，芯片集成了SiP的DDR，外围电路可以极其简单；它支持高清视频解码，包括H.264、H.263、MPEG 1/2/4等，还集成了音频编解码器和I2S/PCM接口，是一款开发简单、性价比较高的产品，也适合用来做入门级的Linux开发板。

开发工具链下载

编译工具链官网：https://www.linaro.org/

或Arm GNU Toolchain，以linaro为例：进入support->downloads可以看到下载页面，点击GNU cross-toolchain binary archives，可以进入对应下载列表，可以看到各个版本的toolchain，这里我使用的latest-7/arm-linux-gnueabi/即gcc-linaro-7.5.0-2019.12-x86_64_arm-linux-gnueabi即可。

![image.png](./20240101210614.jpg)

在 HardWare 目录下，kicad_project 就是 PCB 工程文档，可以下载安装一个 KiCAD 去编辑，当然这个 KiCAD 工程也支持导入立创EDA 中去修改。
