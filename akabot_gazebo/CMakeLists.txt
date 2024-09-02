cmake_minimum_required(VERSION 3.8)
project(akabot_gazebo)

find_package(ament_cmake REQUIRED)
find_package(urdf REQUIRED)

install(
  DIRECTORY config launch models worlds
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
