# [ROS 2 for Beginners Level 2 - TF | URDF | RViz | Gazebo](https://www.udemy.com/course/ros2-tf-urdf-rviz-gazebo/)

# This repository contains the workspace and example files from ROS2 Course 1 that I followed for learning ROS2 basics and robotics simulation.

---

## Inclusions in the Repository

The repository contains examples and exercises from the course, including:

* Creating a robot model using URDF
* Writing and testing ROS2 launch files
* Configuring TFs for robot coordinate frames
* Visualizing robots in RViz
* Spawning and simulating robots in Gazebo
* Controlling robots using sensors, cameras, and actuators
* Implementing a robotic arm with basic motion control
* Adding Gazebo plugins for simulation enhancements

---

## Summary

Includes:

* ROS2 workspace with example packages
* URDF robot models
* Python/C++ nodes
* Launch files for running examples
* Simulation setup for Gazebo and RViz
* Sensor and actuator integration examples

---

## Run Instructions

1. Clone the repository:

```bash
git clone https://github.com/dasunsanjaya080/ROS2_works.git
cd ROS2_works/course_1
```

2. Build the workspace:

```bash
colcon build
```

3. Source the workspace:

```bash
source install/setup.bash
```

4. Run nodes or launch files:

```bash
ros2 run my_robot_bringup <node_executable>
# or
ros2 launch my_robot_bringup my_robot_bringup.launch.xml
```
