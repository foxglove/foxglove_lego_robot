cmake_minimum_required(VERSION 2.8.3)
project(foxglove_lego_robot)

find_package(catkin REQUIRED)
catkin_package()

install(DIRECTORY meshes urdf DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
