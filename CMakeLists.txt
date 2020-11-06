cmake_minimum_required(VERSION 2.8.3)
project(mrs_manipulator)

find_package(catkin REQUIRED COMPONENTS roscpp)
catkin_package()

#add_executable(project src/project.cpp)

#target_link_libraries(project ${catkin_LIBRARIES})

install(DIRECTORY launch
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})

install(DIRECTORY urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})

install(DIRECTORY config
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES mrs_manipulator
#  CATKIN_DEPENDS other_catkin_pkg
#  DEPENDS system_lib
)

include_directories(
include
${catkin_INCLUDE_DIRS}
)

