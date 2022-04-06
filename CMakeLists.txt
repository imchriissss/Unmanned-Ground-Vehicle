cmake_minimum_required(VERSION 2.8.3)
project(pt3a_launch)

find_package(catkin REQUIRED)

catkin_package(
  CATKIN_DEPENDS 
)

install(FILES
  launch/gmapping.launch
  launch/navigation.launch
  launch/simulation.launch
  launch/teleop.launch
  launch/real_robot.launch
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
