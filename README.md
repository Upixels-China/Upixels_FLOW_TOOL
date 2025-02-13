# Upixels_FLOW_TOOL
Upixels Optical flow sensors tool.
Release version 1.2.6 in 20240220.
Upload 2025.02.11.

# 优像光流上位机调参工具仓库说明文档

点击这里切换至英文版本说明文档[Click here to switch to the English version of the instruction document：README_EN.md](./README_EN.md)
 
## 目录结构


```plaintext
仓库根目录
│
├── doc/                     # 帮助文档目录
│   └── 上位机操作指南_V1.0_20231205.pdf  # 中文帮助文档
|   └── EN_Upper computer operation guide_V1.0_20240612.pdf 
|                                        #英文帮助文档
│
└── FLOW_TOOL_v1.2.6_20240220.exe  # 主程序
```
## 下载与使用
 
### 下载最新上位机版本
 
最新的上位机版本可以直接下载此仓库，也可以在Releases下载最新或者历史版本，当前最新版本为`v1.2.6_20250211`（v1.2.6_20250211版本与v1.2.6_20240220版本相同，前者的时间更新为本仓库上传时间）。
 
### 使用说明

- **将模块连接至您的计算器**：通过CH34x系列串口转TTL模块，将光流模块与您的计算机连接，5v -> 5v, GND -> GND, TXD -> RXD, RXD -> TXD。请确保您已经安装CH34x系列的驱动程序，否则您的电脑可能无法正确识别TTL模块。
 
- **运行上位机调参工具**：鼠标双击运行目录中的`FLOW_TOOL_v1.2.6_20240220.exe`运行程序。
 
- **选择正确的串口、波特率以及模块的协议**：请选择正确的串口，如不确定请打开设备管理器查看串口编号。选择正确的波特率以及模块的通信协议，通过上位机你可以切换模块的通信协议，以适配您的需求。（仅较新型号光流模块支持多协议，e.g. Tx系列，LC302-GS。）
 

 
## 联系与支持
 
如有任何问题或需要技术支持，请通过以下方式联系我们：
 
- 官方网址：http://www.upixels.com
- 邮箱：hnyx@upixels.com
- 电话：17773155015
- 地址：长沙高新开发区麓湖路39号金荣央谷金苑A座11楼 

感谢您使用优像光流上位机调参工具！