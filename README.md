# kuka_kr16_config_tutor
MoveIt! Configuration Example file for Controling **KUKA KR16** Over RSI XML.  

# Dependency
- Robot Operating System (ROS) tested on ros-melodic and Ubuntu 18.04 
	- > [http://wiki.ros.org/ROS/Installation](http://wiki.ros.org/ROS/Installation)

**WARN : Replace ros-melodic.... with your ROS DISTRO**
- ROS MoveIt!
	>sudo apt install sudo apt install ros-melodic-moveit*
	
- Position Controller , Joint State Controller 	
	>sudo apt install ros-melodic-joint-* ros-melodic-effort-controllers 
	>sudo apt install ros-melodic-position-controllers

- [kuka_experimental ROS Package](https://github.com/ros-industrial/kuka_experimental)
	- kuka_rsi_hw_interface
	- kuka_kr16_support 
	
Create the catkin workspace first -> below src folder inside catkin workspace
> git clone https://github.com/ros-industrial/kuka_experimental.git
