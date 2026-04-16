cmake_minimum_required(VERSION 3.8)
project(tahiti_b1_description)

find_package(ament_cmake REQUIRED)

# Install all directories
install(
  DIRECTORY urdf meshes launch rviz
  DESTINATION share/${PROJECT_NAME}
)

ament_package()