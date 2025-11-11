# LGDXRobot2 Design

## Overview

LGDXRobot2 is a fully open-source AGV robot that includes the hardware design. This repository contains the controller circuit board design and the robot’s CAD files. It also provides export files for manufacturing the parts without the need to install any software.

- [Homepage](https://lgdxrobot.bristolgram.uk/lgdxrobot2/)
- [Documentation](https://docs.lgdxrobot.bristolgram.uk/lgdxrobot2/ros2/)
- LGDXRobot2 Design: ([GitLab](https://gitlab.com/yukaitung/lgdxrobot2-design) | [GitHub](https://github.com/yukaitung/lgdxrobot2-design))
- LGDXRobot2 MCU: ([GitLab](https://gitlab.com/yukaitung/lgdxrobot2-mcu) | [GitHub](https://github.com/yukaitung/lgdxrobot2-mcu))
- LGDXRobot2 ChassisTuner: ([GitLab](https://gitlab.com/yukaitung/lgdxrobot2-chassistuner) | [GitHub](https://github.com/yukaitung/lgdxrobot2-chassistuner))
- LGDXRobot2 ROS2: ([GitLab](https://gitlab.com/yukaitung/lgdxrobot2-ros2) | [GitHub](https://github.com/yukaitung/lgdxrobot2-ros2))

## Getting Started

### Contorller Board

The `Board` folder contains the design files for the controller board. The board is designed using KiCad, and the exported files are located in the `Board/Exports` folder.

To manufacture the board, simply zip the contents of the `Board/Exports` folder and send it to a PCB manufacturer.

## Chassis

The `Chassis` folder contains the CAD files for the robot. These files require FreeCAD to open. The exported files are located in the `Chassis/Exports` folder.

The root `Chassis` folder includes the designs for all plates and a demo assembly in the `Assembly.FCStd` file. The `Chassis/Components` folder contains CAD files for other parts, which are provided for illustration purposes only.

To manufacture the chassis, you can submit the files in the `Chassis/Exports` folder to a laser cutting service.
