cmake_minimum_required(VERSION 2.8.3)
project(camera_stereo)

find_package(catkin REQUIRED)

catkin_package()


install(DIRECTORY config launch urdf yaml
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
