cmake_minimum_required(VERSION 2.8.3)
project(mitsubishi_rv7f_gazebo)
find_package(catkin REQUIRED)

catkin_package()

find_package(roslaunch)
roslaunch_add_file_check(test/rv7f_empty_world_launch_test.xml)
