# ROS2 Humble Differential Drive Robot Simulation
A comprehensive simulation project for a two-wheeled differential drive robot using ROS2 Humble, Gazebo, and Rviz2. This project integrates the Navigation2 framework to enable both single-point and waypoint navigation capabilities.
## Overview
This repository contains a complete simulation stack for a differential drive robot, including:

- URDF/Xacro robot description
- Gazebo simulation environment
- ROS2 Humble nodes for control and perception
- Navigation2 integration for autonomous navigation
- Rviz2 configuration for visualization

The robot is equipped with essential sensors (LiDAR, IMU, and odometry) to enable SLAM and navigation in unknown environments.
## Features
Accurate Dynamics: Realistic differential drive kinematics and dynamics
Sensor Simulation: LiDAR, IMU, and wheel odometry
Autonomous Navigation:
Single point goal navigation
Waypoint following
Obstacle avoidance
SLAM Capabilities: Simultaneous Localization and Mapping
Visualization: Comprehensive Rviz2 configuration
## Prerequisites
- ROS2 Humble
- Gazebo (Garden or newer)
- Navigation2
- colcon
- xacro
- tf2
## Installation
1. Create a ROS2 workspace:
```bash
mkdir -p ~/ros2_ws/src
cd ~/ros2_ws/src
```

2. Clone this repository:
```bash
git clone https://github.com/yourusername/ros2-differential-drive-simulation.git
```

3. Install dependencies:
```bash
cd ~/ros2_ws
rosdep install -i --from-path src --rosdistro humble -y
```

4. Build the workspace:
```bash
colcon build
source install/setup.bash
```
## Usage
### Basic Simulation
Launch the robot in a Gazebo environment:
```bash
ros2 launch differential_drive_gazebo empty_world.launch.py
```

### Navigation



## Project Structure



## Screenshots



## Acknowledgments
- ROS2 Documentation
- Navigation2 Framework
- Gazebo Simulator
