cmake_minimum_required(VERSION 2.8.3)
project(yumi_moveit_demos)

add_compile_options(-std=c++11)

# Load catkin and all dependencies required for this package
find_package(catkin REQUIRED COMPONENTS

)

# Declare catkin package
catkin_package(
  CATKIN_DEPENDS
  LIBRARIES ${PROJECT_NAME}
)

include_directories(include ${Boost_INCLUDE_DIR} ${catkin_INCLUDE_DIRS})


