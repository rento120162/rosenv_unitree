[![ros2 workflow](https://github.com/hrjp/rosenv/actions/workflows/ros2-humble-image-build.yml/badge.svg)](https://hub.docker.com/repository/docker/hrjp/ros2)

![license](https://img.shields.io/github/license/KobeKosenRobotics/rosenv_for_unitree)
![size](https://img.shields.io/github/repo-size/KobeKosenRobotics/rosenv_for_unitree)
![commit](https://img.shields.io/github/last-commit/KobeKosenRobotics/rosenv_for_unitree/main)

# rosenv_for_unitree
This repository is for making ROS2 docker on Unitree robots (Jetson ARM64)  
Docker container include ROS2humble, and necesarry packages for control Unitree robots with Low-Level (i checked Go2 and G1)
## reference
- [https://github.com/hrjp/rosenv](https://github.com/hrjp/rosenv)
- [https://github.com/IntelRealSense/realsense-ros](https://github.com/IntelRealSense/realsense-ros)
- [https://github.com/unitreerobotics/unitree_ros2](https://github.com/unitreerobotics/unitree_ros2)
- [https://github.com/jetsonhacksnano/installLibrealsense](https://github.com/jetsonhacksnano/installLibrealsense)
- [https://github.com/ros2/rosidl_dds.git](https://github.com/ros2/rosidl_dds.git)
# Setup
## 1.git colne 
```bash
cd
git clone https://github.com/rento120162/rosenv_unitree.git
```

## 2. make container
```bash
chmod +x rosenv_for_unitree/docker/humble_amd64/run.bash
./rosenv_for_unitree/docker/humble_amd64/run.bash -n humble
```
