# Turtle-Bio-Inspired Robot for Turtle Monitoring

## Project Description

This repository presents a bio-inspired mobile robot designed to monitor the movement and health of turtles in controlled or natural environments. The robot mimics turtle-like locomotion using a differential drive base and integrates a rotating camera system to track nearby turtles using a trained YOLOv5 detection model.

It is built on ROS 2 and is intended for environmental research, wildlife tracking, and bio-robotics studies.

## Objectives

- Monitor turtle movement in real-time using an autonomous robot.
- Detect and track turtles with YOLOv5 and a rotating camera.
- Collect movement data for health or behavioral analysis.
- Use ROS 2 for modular robot control and camera data processing.

## Hardware Overview
![IMG_0572](https://github.com/user-attachments/assets/3b19b37b-cea0-4df8-9960-9dc3053b9b6c)

- Differential drive mobile robot
- Pan-tilt rotating camera 
- Onboard computer Raspberry Pi 4
- Power supply LiPo battery 
- Optional: Temperature/humidity sensors for environmental data

## Software Stack

- ROS 2 
- YOLOv5 (PyTorch) for turtle detection
- OpenCV for image processing
- Custom ROS 2 nodes for motion control, camera rotation, and detection

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/mohammedabdelsaboor/Turtle-Bio-inspired-Robot.git
