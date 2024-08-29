# TurtleSim_Catch_Them_All_Ros2_Basics
A ROS2 project based on TurtleSim simulation, in which a master turtle aims to catch all the other turtles in the environment. New turtles are spawned periodically and the master turtle always catches the closest turtle to it in a given moment.

![turtlesim_catch_them_all](https://github.com/user-attachments/assets/108d37e0-04cc-4c67-ad22-c605ea37bbca)

## Environment setup
- Make sure you have a ROS2 workspace configured, such as taught in the ROS2 Official Documentation: https://docs.ros.org/en/foxy/Tutorials/Beginner-Client-Libraries/Creating-A-Workspace/Creating-A-Workspace.html
- After that, clone this repository inside the ROS2 workspace and build packages
```shell
colcon build
```
- Then run the launch file
```shell
ros2 launch turtle_bringup turtlesim_catch_them_all.launch.py
```
