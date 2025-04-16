# Upixels_FLOW_TOOL
Upixels Optical flow sensors tool.
Release version 1.2.6 in 20240220.
Upload 2025.02.11.

# Upixels Optical Flow Upper Computer Parameter Adjustment Tool Repository Documentation
 
点击这里切换至中文版本说明文档[Click here to switch to the Chinese version of the instruction document：README_CN.md](./README_CN.md)

## Directory Structure

```plaintext
Repository Root Directory
│
├── doc/                     # Help Documentation Directory
│   └── 上位机操作指南_V1.0_20231205.pdf  # Chinese Help Documentation
│   └── EN_Upper computer operation guide_V1.0_20240612.pdf 
│                                        # English Help Documentation
│
└── FLOW_TOOL_v1.2.6_20240220.exe  # Main Program
```
## Download and Usage
 
### Download the Latest Upper Computer Version
 
The latest upper computer version can be directly downloaded from this repository, or you can download the latest or historical versions from Releases. The current latest version is`v1.2.6_20250211` (the v1.2.6_20250211 version is the same as the v1.2.6_20240220 version, with the former's time updated to the upload time of this repository).
 
### Usage Instructions

- **Connect the Module to Your Computer**：Use a CH34x series serial-to-TTL module to connect the optical flow module to your computer, 5v -> 5v, GND -> GND, TXD -> RXD, RXD -> TXD. Ensure that you have installed the CH34x series driver, otherwise your computer may not correctly recognize the TTL module.
 
- **Run the Upper Computer Parameter Adjustment Tool**：Double-click`FLOW_TOOL_v1.2.6_20240220.exe`in the runtime directory to run the program.
 
- **Select the Correct Serial Port, Baud Rate, and Module Protocol**：Choose the correct serial port; if unsure, open the Device Manager to check the serial port number. Select the correct baud rate and the module's communication protocol. Through the upper computer, you can switch the module's communication protocol to suit your needs. (Only newer model optical flow modules support multiple protocols, e.g., Tx series, LC302-GS.)
 

 
## Contact and Support
 
If you have any questions or need technical support, please contact us through the following methods:
 
- Official Website: http://www.upixels.com
- Email: @upixels.com
- Phone: 17773155015
- Address: 11th Floor, Building A, Jinrong Yanggu Golden Garden, Luhu Road No. 39, Changsha High-Tech Development Zone (China)

Thank you for using the Upixels Optical Flow Upper Computer Parameter Adjustment Tool!
