cmake_minimum_required(VERSION 2.8)
project(open_karto)

find_package(catkin REQUIRED)

set(KARTO_LIB_TYPE SHARED)
add_subdirectory(source)

catkin_package(
  LIBRARIES OpenKarto
  )

#install(DIRECTORY include/${PROJECT_NAME}/
#  DESTINATION ${CATKIN_PACKAGE_INCLUDE_DESTINATION}
#)

