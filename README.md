# RIS-IE4060 Assignment 02 - ROS2 Maze Simulation

## 🧩 Author
**Hansika J. A. J (IT22346018)**

## 🧠 Description
This project contains the ROS2 simulation environment for a TurtleBot3 navigating a custom maze world created for the IE4060 Robotics and Intelligent Systems course.

## ⚙️ Package Structure
- launch/ — Launch files for Gazebo and SLAM
- worlds/ — Custom maze world files
- my_maze/ — Model definition (SDF and config)
- src/ — Source code if needed

## 🚀 Run Instructions
```bash
cd ~/ros2_ws
colcon build
source install/setup.bash
ros2 launch my_simulations my_world.launch.py
```

## 🧠 Technologies
- ROS2 Jazzy
- Gazebo Sim
- TurtleBot3 Burger
- SLAM Toolbox


