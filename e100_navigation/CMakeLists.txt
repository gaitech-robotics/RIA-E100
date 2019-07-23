cmake_minimum_required(VERSION 2.8.3)
project(e100_navigation)

find_package(catkin REQUIRED COMPONENTS roscpp rospy std_msgs std_srvs geometry_msgs)

catkin_package(
)

include_directories(
# include
# ${catkin_INCLUDE_DIRS}
)

install(
  DIRECTORY launch config maps
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)