cmake_minimum_required(VERSION 3.10)
project(HelloWorld)
add_executable(app main.cpp src/HelloWorld.cpp)
target_include_directories(app PRIVATE include)
