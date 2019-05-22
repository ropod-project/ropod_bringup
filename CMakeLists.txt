cmake_minimum_required(VERSION 2.8.3)
project(ropod_bringup)

find_package(catkin REQUIRED)

catkin_package(
  CATKIN_DEPENDS
    hokuyo_node
    openni2_launch
    robot_state_publisher
    tf
)
