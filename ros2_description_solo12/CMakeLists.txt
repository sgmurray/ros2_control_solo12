cmake_minimum_required(VERSION 3.5)
project(ros2_description_solo12)

find_package(ament_cmake REQUIRED)

install(
  #DIRECTORY meshes ros2_control urdf gazebo config
  DIRECTORY meshes ros2_control urdf 
  DESTINATION share/${PROJECT_NAME}
)

ament_package()