cmake_minimum_required(VERSION 2.8.3)
project(recorded_motions)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED COMPONENTS
  baxter_interface
  rospy
)

catkin_python_setup()

catkin_package(
  CATKIN_DEPENDS baxter_interface rospy
)

