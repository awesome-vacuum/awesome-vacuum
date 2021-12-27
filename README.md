# awesome-vacuum

A curated list of free and open source software and hardware projects which can be used to build and control a robot vacuum.

--------------------

- [awesome-vacuum](#awesome-vacuum)
- [Hardware](#hardware)
  - [IMU](#imu)
  - [LIDAR](#lidar)
  - [Projects](#projects)
- [Software](#software)
  - [Frameworks](#frameworks)
  - [SLAM](#slam)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

--------------------

# Hardware

**[`^        back to top        ^`](#)**

## IMU

**[`^        back to top        ^`](#)**

A IMU helps to make localization much more stable by providing accelerometer, gyroscope and some even magnetometer data.
[cartographer](https://github.com/cartographer-project/cartographer) can easily be setup with IMU to improve localization.

- [MPU6050](https://playground.arduino.cc/Main/MPU-6050/) - IMU sensor combining a MEMS accelerometer and a MEMS gyro on a single chip.

## LIDAR

**[`^        back to top        ^`](#)**

A LIDAR (Light Detection and Ranging) can create an accurate representation of its surroundings by utilizing a laser and a light sensor to measure TOF (Time of Flight). Devices are available as 2D and 3D variants, although the 3D variants are still pretty expensive and do not add much value to the "robot vacuum" use case.

- [camsense-X1](https://github.com/Vidicon/camsense-X1) - Unofficial reverse engineering of a Chinese LiDAR. `GPL-3.0`
- [RPLIDAR A Series](https://www.slamtec.com/en/Lidar/A1) - 360 Degree Laser Scanner with ROS integration and up to 16K samples per second.

## Projects

**[`^        back to top        ^`](#)**

A list of full blown projects to create a robot vacuum.

- [CleanBOT](https://www.instructables.com/CleanBOT/) - DIY bluetooth controlled robot vacuum built from wood and scrap electronics.
- [DIY Vacuum Robot by CesNieto](https://www.instructables.com/Build-Your-Own-Vacuum-Robot/) - DIY robot vacuum built using 3D printing and an Arduino Uno.
- [Robot Vacuum Cleaner MK2](https://www.myminifactory.com/object/3d-print-101108) - DIY robot vacuum built using 3D printing and an Arduino Nano. `BY-NC-SA`

# Software

**[`^        back to top        ^`](#)**

- [Bumper](https://github.com/bmartin5692/bumper) - A standalone and self-hosted implementation of the central server used by Ecovacs vacuum robot. `GPL-3.0` `Python`
- [Dustcloud](https://github.com/dgiese/dustcloud) - Xiaomi Smart Home Device Reverse Engineering and Hacking. `GPL-3.0` `Various`
- [Roborock Oucher](https://github.com/porech/roborock-oucher) - An utility to make the Roborock / Xiaomi MI Vacuum Cleaner scream "Ouch!" (or everything else) everytime it bumps into something `MIT` `golang`
- [Valetudo](https://github.com/Hypfer/Valetudo) - Cloud-free control webinterface for vacuum robots. `Apache-2.0` `JavaScript`
- [I can't belive it's not Valetudo](https://github.com/Hypfer/ICantBelieveItsNotValetudo) - Valetudo companion service (Map Rendering) `Apache-2.0` `JavaScript`
- [Valetudo RE](https://github.com/rand256/valetudo) - Experimental vacuum software, cloud free (Valetudo Fork) `Apache-2.0` `JavaScript`
- [valetudo mapper](https://github.com/rand256/valetudo-mapper) - Valetudo companion service (Map Rendering, ICantBelieveItsNotValetudo Fork) `Apache-2.0` `JavaScript`
- [FreeCong.ga](https://freecon.ga) - Valetudo implementation for Cecotec Conga Vacuums. [Freeconga Organization](https://github.com/freeconga) in Github. `Apache-2.0`, `GPL-3.0`
- [Congatudo](https://github.com/freeconga/congatudo-add-on) Freecon.ga project to have Valetudo in the Home Assistant as addon intead of use standalone installation into the vacuum. `GPL-3.0` `Shell`
- [OpenDoñita](https://gitlab.com/rastersoft/opendonita) - Add local support for previous Congas 1490. `GPL-3.0` `Python`

## Frameworks

**[`^        back to top        ^`](#)**

- [Gobot](https://github.com/hybridgroup/gobot/) - Golang framework for robotics, drones, and the Internet of Things (IoT).  `Apache-2.0` `golang`
- [ROS (Robot Operating System)](https://wiki.ros.org/) - Provides libraries and tools to help software developers create robot applications. It provides hardware abstraction, device drivers, libraries, visualizers, message-passing, package management, and more. `BSD` `Various`

## SLAM

**[`^        back to top        ^`](#)**

SLAM (Simultaneous Localization and Mapping) is used to build a map by repeatedly scanning surrounding area and through that enable the robot to localize itself within that environment.

- [BreezySLAM](https://github.com/simondlevy/BreezySLAM) - Simple, efficient, open-source package for Simultaneous Localization and Mapping. `LGPLv3` `Various`
- [cartographer](https://github.com/cartographer-project/cartographer) - A system that provides real-time simultaneous localization and mapping (SLAM) in 2D and 3D across multiple platforms and sensor configurations. `Apache-2.0` `C++`
- [OpenVSLAM](https://github.com/xdspacelab/openvslam) - A Versatile Visual SLAM Framework. `2-Clause BSD` `C++`
- [ROS SLAM](https://github.com/ros-perception/slam_gmapping) - A ROS wrapper for OpenSlam's Gmapping. `BSD` `C++`

--------------------


# Other Awesome Lists

* [Awesome Robotic Tooling](https://github.com/protontypes/awesome-robotic-tooling)


# Contributing

You know a software or hardware project that is not on this list yet? Contributions are very much welcome! Have a look at the [Contribution Guidelines](.github/CONTRIBUTING.md) to learn how you can add projects to this list.
