cmake_minimum_required(VERSION 2.8.3)
project(jvrc_task_models)

find_package(catkin REQUIRED COMPONENTS
  gazebo_ros
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)

# Turns out this is not required
#catkin_add_env_hooks(10.gazebo_model_path_setup SHELLS bash)
