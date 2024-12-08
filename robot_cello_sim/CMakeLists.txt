cmake_minimum_required(VERSION 3.5)
project(robot_cello_sim)

find_package(ament_cmake REQUIRED)

install(DIRECTORY config launch models urdf
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
