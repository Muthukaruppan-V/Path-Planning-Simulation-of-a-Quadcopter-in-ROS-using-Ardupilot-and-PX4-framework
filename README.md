# Path Planning Simulation of a Quadcopter in ROS using Ardupilot and PX4 framework

## Overview

This project focuses on designing and simulating autonomous drones for precision agriculture. Developed during an internship at NIT Calicut, it demonstrates how robotics and AI can automate key tasks such as fruit harvesting, wildlife deterrence, and pest control in farming.

The drone system is built and tested using ROS2 and Gazebo simulation environments, integrated with PX4 and ArduPilot flight control frameworks. The simulations include 2D and 3D mission execution scenarios, including autonomous waypoint navigation.

## Applications

1. **Mango Harvesting**
   A custom cutting mechanism is simulated for detecting and harvesting mangoes using a robotic gripper and precision tools.

2. **Monkey Scaring**
   Real-time detection of monkeys using deep learning (YOLOv8), followed by triggering a deterrent system (e.g., pepper spray or sound).

3. **Palm Tree Pest Detection**
   Drones detect infected palm trees using visual analysis and perform targeted pesticide spraying only on affected areas.

## Key Features

* Drone simulation using **ROS2, PX4, ArduPilot, and Gazebo**
* **URDF models** generated from Fusion 360 for accurate physical design
* **Mission planning** via QGroundControl with autonomous waypoint navigation
* Use of **YOLOv8** for real-time object detection (mangoes, monkeys, pests)
* Integration of **robotic cutting mechanisms** and precision spraying tools
* Setup of **Micro XRCE-DDS** for communication between ROS2 and PX4
* 2D & 3D simulation using MAVROS and Rviz for visualization

## Technologies Used

- [ROS2 Humble](https://docs.ros.org/en/humble/index.html) – Open-source robotics middleware
- [PX4 Autopilot](https://px4.io/) ([GitHub](https://github.com/PX4/PX4-Autopilot)) – Drone flight control software
- [ArduPilot SITL](https://ardupilot.org/dev/docs/sitl-simulator-software-in-the-loop.html) ([GitHub](https://github.com/ArduPilot/ardupilot)) – Software-in-the-loop simulation for drones
- [Ignition Gazebo Fortress](https://gazebosim.org/docs/fortress) – 3D robot simulation environment
- [Micro XRCE-DDS Agent](https://github.com/eProsima/Micro-XRCE-DDS-Agent) – DDS communication for ROS2 and PX4
- [Python](https://www.python.org/) – Used for scripting, control, and automation
- [MAVROS](https://github.com/mavlink/mavros) – MAVLink communication bridge between PX4/ArduPilot and ROS
- [QGroundControl](https://docs.qgroundcontrol.com/master/en/) – Ground control station for flight mission setup
- [Fusion 360](https://help.autodesk.com/view/fusion360/ENU/) + [URDF Export Plugin](https://github.com/ros-industrial/fusion360_to_urdf) – CAD modeling and ROS-compatible export
- [YOLOv8 - Ultralytics] – Real-time object detection model

## Outcomes

* Completed full-stack simulation of three agricultural drone applications
* Built a modular and extensible ROS2 environment for drone simulation
* Integrated mission control and visualization tools (QGroundControl, Rviz)
* Demonstrated object detection, precision harvesting, and autonomous spraying

## Conclusion

This simulation-based project shows the potential of drone and AI technologies to solve real agricultural challenges. It lays the foundation for future real-time implementations, especially in high-risk or labor-intensive farm tasks. The architecture is modular, making it suitable for deployment and scale in smart farming solutions.
