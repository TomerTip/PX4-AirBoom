# PX4 AirBoom

## Install
Follow installation instructions here, install PX4 (*this fork*), Gazebo, QGroundControl: 
https://github.com/MrStealYoCurls/Gazebo-PX4-Setup-Guide

### PX4-AirBoom
```bash
git clone --recurse-submodules git@github.com:TomerTip/PX4-AirBoom.git -b airboom
git submodule update --recursive
```

## Run
```bash
cd PX4-AirBoom
make px4_sitl gazebo-classic-iris_fpv_cam_down__baylands
```

![image](https://github.com/user-attachments/assets/b14db8bf-c7b5-478e-bddb-3dc52518a441)
