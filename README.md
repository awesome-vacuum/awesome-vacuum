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
- [kaiaai LDS](https://github.com/kaiaai/LDS) - Arduino library with a single API for 20+ low-cost 2D LiDARs, including ones salvaged from robot vacuums (Xiaomi LDS02RR, Neato XV11, Camsense X1, YDLIDAR, ...). `Apache-2.0` `C++`
- [RPLIDAR A Series](https://www.slamtec.com/en/Lidar/A1) - 360 Degree Laser Scanner with ROS integration and up to 16K samples per second.

## Projects

**[`^        back to top        ^`](#)**

A list of full blown projects to create a robot vacuum.

- [CleanBOT](https://www.instructables.com/CleanBOT/) - DIY bluetooth controlled robot vacuum built from wood and scrap electronics.
- [DIY Vacuum Robot by CesNieto](https://www.instructables.com/Build-Your-Own-Vacuum-Robot/) - DIY robot vacuum built using 3D printing and an Arduino Uno.
- [DIY Robot Vacuum by Mr. Cookie](https://hackaday.io/project/182176-diy-robot-vacuum) - DIY robot vacuum built from an Arduino, MDF and widely available parts, without custom PCBs. Laser-cut files for the frame are provided.
- [OOMWOO](https://github.com/makerspet/oomwoo) - Open source robot vacuum you build yourself, using a Raspberry Pi, 3D printing, ROS 2 and Home Assistant. `Apache-2.0` `Python`
- [OOMWOO PCB](https://github.com/makerspet/oomwoo-pcb) - I/O board (STM32 with motor drivers and sensor inputs) for the OOMWOO robot vacuum. `Apache-2.0`
- [Robot Vacuum Cleaner MK2](https://www.myminifactory.com/object/3d-print-101108) - DIY robot vacuum built using 3D printing and an Arduino Nano. `BY-NC-SA`

# Software

**[`^        back to top        ^`](#)**

- [Bumper](https://github.com/bmartin5692/bumper) - A standalone and self-hosted implementation of the central server used by Ecovacs vacuum robot. `GPL-3.0` `Python`
- [CleanIt](https://github.com/Sollimann/CleanIt) - Open-source autonomy software using gRPC for the Roomba series robot vacuum cleaners. Under development. `MIT` `Rust`
- [dorita980](https://github.com/koalazak/dorita980) - Unofficial SDK to control iRobot Roomba and Braava robots over the local network. `MIT` `JavaScript`
- [Dreame Vacuum](https://github.com/Tasshack/dreame-vacuum) - Home Assistant integration for Dreame robot vacuums with map support. `MIT` `Python`
- [Dustcloud](https://github.com/dgiese/dustcloud) - Xiaomi Smart Home Device Reverse Engineering and Hacking. `GPL-3.0` `Various`
- [Robot Info](https://robotinfo.dev/) - Overview of robot vacuums with hardware details and information on which models can be rooted.
- [python-miio](https://github.com/rytilahti/python-miio) - Python library and console tool for controlling Xiaomi smart appliances, including vacuums. `GPL-3.0` `Python`
- [python-roborock](https://github.com/python-roborock/python-roborock) - Python library and console tool for controlling Roborock vacuums. `Apache-2.0` `Python`
- [Xiaomi Cloud Map Extractor](https://github.com/PiotrMachowski/Home-Assistant-custom-components-Xiaomi-Cloud-Map-Extractor) - Home Assistant integration showing a live map for Xiaomi, Roborock, Viomi, Roidmi and Dreame vacuums without rooting. `MIT` `Python`
- [Xiaomi Vacuum Map Card](https://github.com/PiotrMachowski/lovelace-xiaomi-vacuum-map-card) - Home Assistant Lovelace card to control map-based vacuums (Xiaomi, Valetudo, Neato, Roomba, Ecovacs, ...). `MIT` `TypeScript`
- [Roborock Oucher](https://github.com/porech/roborock-oucher) - An utility to make the Roborock / Xiaomi MI Vacuum Cleaner scream "Ouch!" (or everything else) everytime it bumps into something `MIT` `golang`
- [VacuumTiger](https://github.com/codetiger/VacuumTiger) - Modular, configuration-driven open source firmware for robot vacuums, with a generic TCP protocol for SLAM applications. `MIT` `Rust`
- [Valetudo](https://github.com/Hypfer/Valetudo) - Cloud-free control webinterface for vacuum robots. `Apache-2.0` `JavaScript`
- [I can't belive it's not Valetudo](https://github.com/Hypfer/ICantBelieveItsNotValetudo) - Valetudo companion service (Map Rendering) `Apache-2.0` `JavaScript`
- [Valetudo RE](https://github.com/rand256/valetudo) - Experimental vacuum software, cloud free (Valetudo Fork) `Apache-2.0` `JavaScript`
- [vacuum (zvldz)](https://github.com/zvldz/vacuum) - Firmware builder for first and second generation Roborock vacuums. `GPL-3.0` `Shell`
- [valetudo mapper](https://github.com/rand256/valetudo-mapper) - Valetudo companion service (Map Rendering, ICantBelieveItsNotValetudo Fork) `Apache-2.0` `JavaScript`
- [FreeCong.ga](https://freecon.ga) - Valetudo implementation for Cecotec Conga Vacuums. [Freeconga Organization](https://github.com/freeconga) in Github. `Apache-2.0`, `GPL-3.0`
- [Congatudo](https://github.com/freeconga/congatudo-add-on) Freecon.ga project to have Valetudo in the Home Assistant as addon intead of use standalone installation into the vacuum. `GPL-3.0` `Shell`
- [OpenDoñita](https://gitlab.com/rastersoft/opendonita) - Add local support for previous Congas 1490. `GPL-3.0` `Python`
- [MQTT Vacuum Camera](https://github.com/sca075/mqtt_vacuum_camera) - Home Assistant camera integration to render the maps of vacuums connected via MQTT (Valetudo, Valetudo RE, Congatudo). `Apache-2.0` `Python`

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
