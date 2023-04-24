cmake_minimum_required(VERSION 3.5)
project(franka_robotiq_setup)
find_package(ament_cmake REQUIRED)

add_subdirectory(description)
add_subdirectory(moveit_config)

ament_package()
