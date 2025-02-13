# BEE35-DAQ-LIDAR
An autonomous quad-rotor using MID-360


## 1. Project Description

>This project aims at developing an autonomous drone mainly based on MID-360 LiDAR.
The drone is built upon FPV drone kit "BEE-35", for what it is called "**BEE35-DAQ-LIDAR**".
Powered by open-souce code [**FAST-LIO2**](https://github.com/hku-mars/FAST_LIO) and [**ego-planner**](https://github.com/ZJU-FAST-Lab/ego-planner)(or you can develop your own), 
this drone can execute complex missions such as auto exploration and obstacle avoidance.

A following photo shows how it looks when well assembled. 

<img src="Images\BEE35_DAQ_LIDAR_01.jpg" alt="wait" width="700">



## 2. File Description 

***The File Tree***
```
- Code
- Firmware  
  - External-repo
- Hadware
  - BOM.xlsx
  - Mech
    - 3D_Printing_Parts
    - Open_Source_3DModels
    - PCB_Models
  - PCB
    - BEE35-PWDIS-AIO
    - HDMI-D-Sink
- Images
```


## 3. Bill of Matreials

### A. Ready-made modules
| Name | Function | Quantity |Price(RMB)|
|:---------:|:---------:|:---------:|:--:|
| NxtPX4-v2         | Flight Controller         | 1 |x|
| BlueBird 48K 30A  | 4in1 ESC                  | 1 |x|
| T-MOTOR V2004     | Motor                     | 4 |x|
| BEE-35            | FPV drone kit             | 1 |x|
| MTF-01            | Opticflow + Laser Ranging | 1 |x|

### B. PCB

### C. Miscellaneous


## 4. Tutorial for Assembly

## 5. Code Deployment

## 6. Acknowledgments

Thanks for the following projects:

- [CU-Astro自主探索无人机室内外飞行演示：3.5寸紧凑型 (cuhk-usr-group)](https://www.bilibili.com/video/BV1G6HmeqEZR/?spm_id_from=333.1387.favlist.content.click)
- [Nxt-FC DUAL @HKUST Aerial Robotics Group](https://github.com/HKUST-Aerial-Robotics/Nxt-FC)
- [FAST-LIO2 @HKU-MARS](https://github.com/hku-mars/FAST_LIO)
- [ego-planner @ZJU-FAST-Lab](https://github.com/ZJU-FAST-Lab/ego-planner)
- [Fast-Drone-250 @ZJU-FAST-Lab](https://github.com/ZJU-FAST-Lab/Fast-Drone-250)



## 7. Todo List
- [ ] Compelte the Readme
- [ ] BEE-35-PWDIS-AIO Direction of XT60 need to be changed
- [ ] FAST-LIO2+ego test
- [ ] too much todo