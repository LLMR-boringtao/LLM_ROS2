# LLM_P3_ROS2

## Overview

This project is a ROS2 package that simulates a robot in Gazebo and Rviz2. The robot is a differential drive robot that can move around in a Gazebo world. The robot is equipped with a camera and a lidar. 

## Dependencies

This project was developed under Ubuntu 20.04 and ROS2 Foxy. It requires the following packages:

- ROS2 Foxy
- Gazebo 11
- Rviz2

## Build Instructions

To build the project, create a workspace and clone the repository in it. Then, build the workspace with the following commands:

```
colcon build
```

## Run Instructions

To run the project, source the workspace and launch the launch file with the following commands:

``` 
source devel/setup.bash
ros2 launch world.launch.py
```

## Author

This project was developed by [Boringtao](
https://twitter.com/BoringtaoL22644).

```
