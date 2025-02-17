# E2E 
### E2E: Targetless Automatic Edge-2-Edge extrinsic calibration algorithm.

### 📢 Source Code Public
Since our work is still in the review process of IEEE TIM, and this work is currently linked to project, it is temporarily confidential.
After the paper is accepted and the project is completed, the code will be open source.

### 📬 Contact
If you have any questions, please feel free to contact: Weijie Zhu [zwj@seu.edu.cn]

## 1. Introduction
### E2E is a targetless, automatic edge-to-edge calibration method based solely on laser reflectivity, aimed at enhancing calibration accuracy and feature consistency in the LiDAR-Camera calibration (LCC) task. Traditional methods primarily focus on the 3D information of LiDAR point clouds for feature detection. In contrast, the proposed method leverages the superior capabilities of laser reflectivity to perceive color, depth, and material properties. This strategy enables robust edge feature consistency in 2D, thereby enhancing overall calibration accuracy.

<div align="center">
    <img src="pics/Intro/overview.png" width = 100% >
</div>

## 2. Hardware Platform and Dataset
### 2.1 To facilitate the experiment, we designed a handheld scanning device.
<div align="center">
    <img src="pics/Hardware/platform_white.png" width = 30% >
</div>

### 2.2 Main material lists (only for reference)
| Item  | Pics  | Purchasing list  |
| :------------: | :------------: | :------------: |
| Livox Mid-70 LiDAR  | <img src="./pics/livox_avia.png" width=20%  /> | [Livox Avia](https://store.dji.com/hk-en/product/livox-avia) |
| CMOS | <img src="./pics/cmos.jpg" width=20%  /> | [MV-CA013-21UC ](https://www.hikrobotics.com/en/machinevision/productdetail?id=1314&pageNumber=1&pageSize=50) |
| Camera Len | <img src="./pics/len.jpg" width=20%  /> | [ MVL-HF0628M-6MPE](https://m.tb.cn/h.gXmtLRX2UYzGDzH?tk=hIS7WGPOY0y) |
| STM32 | <img src="./pics/stm32.jpg" width=25%  /> | [STM32F103C8T6](https://m.tb.cn/h.ggkS9Kp?tk=orRfWz6M784) |
| Screen | <img src="./pics/screen.jpg" width=25%  /> | [IPS Screen 10''](https://m.tb.cn/h.ggkhQ7e?tk=LntBWz6mHDL) |
| Battery | <img src="./pics/battery.jpg" width=30%  /> | [4800mah](https://m.tb.cn/h.g5vJI7a?tk=ofKdWz6OYQm) |
| TTL to USB | <img src="./pics/usb.jpg" width=30%  /> | [TTL to USB](https://m.tb.cn/h.gWzMxzBSkhSqkH3?tk=N1j3WEzIP9u) |
| TTL to 485 | <img src="./pics/485.jpg" width=30%  /> | [TTL to 485](https://m.tb.cn/h.g3SEkso?tk=eER4WEzFYmP) |

## 3. Experiment Result of Natural Scenes
### 3.1 The experimental scenes, illustrated in below figure, include eight randomly selected natural environments such as corridors, walls, buildings, and parking area. 
<div align="center">
    <img src="pics/Intro/scene.png" width = 100% >
</div>

### 3.2 The exmaple dataset can be download from the link below
- 🔴Password: 2025
- 🔓[**BaiduNetDisk(百度网盘)**]([https://pan.baidu.com/s/1oz3unqsmDnFvBExY5fiBJQ?pwd=i964](https://pan.baidu.com/s/1ahdxv8vL05-QIoMGVL6S6Q?pwd=2025)).


### 3.3 The calibration result of overlapping map between the laser refectivity and original image.
<div align="center">
    <img src="pics/Intro/result.png" width = 100% >
</div>
