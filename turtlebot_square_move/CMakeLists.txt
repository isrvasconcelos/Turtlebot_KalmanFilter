cmake_minimum_required(VERSION 2.8.3)
project(turtlebot_square_move)

## Compile as C++11, supported in ROS Kinetic and newer
add_compile_options(-std=c++11)

find_package(catkin REQUIRED COMPONENTS
  roscpp
  rospy
  sensor_msgs
  std_msgs
  tf
)

catkin_package()

include_directories(
  ${catkin_INCLUDE_DIRS}
)

include_directories(include ${catkin_INCLUDE_DIRS})
add_executable(turtlebot_square_move src/turtlebot_square_move.cpp)
target_link_libraries(turtlebot_square_move ${catkin_LIBRARIES})

