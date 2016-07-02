cmake_minimum_required(VERSION 2.8.3)
project(mbzirc_gazebo)

## end effector taking drilling part
# copyright by Luan Doan 
# email: luandoan263@gmail.com
# url repository: https://github.com/luandoan/mbzirc
# CMS Lab, Virginia Tech - July 2016

find_package(catkin REQUIRED COMPONENTS
  gazebo_ros
)


catkin_package()


include_directories(
  ${catkin_INCLUDE_DIRS}
)


