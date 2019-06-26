cmake_minimum_required(VERSION 2.8.3)
project(e100_description)

find_package(catkin REQUIRED)

catkin_package(
)

include_directories(
# include
# ${catkin_INCLUDE_DIRS}
)

install(
  DIRECTORY include launch
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)