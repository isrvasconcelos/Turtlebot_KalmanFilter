# Turtlebot_KalmanFilter
Gazebo simulation comparing attempts to draw a square using Kobuki on gazebo with simple walking and correcting the trajectory with Kalman Filter.

These scripts runs on Ubuntu 14.04 and ROS Indigo and requires superuser permissions.
	sudo -s

Add the packages stored at this repository on your catkin_ws/src.
At catkin_ws/, run the command to compile the packages.
	catkin_make

First open Gazebo by typing:
	roslaunch turtlebot_gazebo turtlebot_world.launch

Then, open a new console tab run the kalman filter node.
	roslaunch robot_pose_ekf robot_pose_ekf

Change directory to catkin_ws/devel/lib/turtlebot_quare_move/ and open a new console inside this folder, running:
	./turtlebot_quare_move

Inspect the behavior of the turtlebot by listening the odometry topic, typing on console:
	rostopic echo /odom
