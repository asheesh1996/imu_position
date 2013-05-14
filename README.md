imu_position
============

install:
--------
sudo apt-get install git-core  
git clone https://github.com/eemmyy23/imu_position.git  
rosdep install imu_position  
rosmake imu_position
install with rosws:
------------------
roscd  
rosws set imu_position https://github.com/eemmyy23/imu_position.git --git  
rosws update imu_position  

usage:
------
rosrun imu_position imu_position  
rosrun imu_position imu_position imu/data:=/your_imu_topic/data

dynamic reconfigure:
--------------------
rosrun dynamic_reconfigure reconfigure_gui
rosrun imu_position dynamic_reconfigure

demo:
-----
using rosbag files:  
