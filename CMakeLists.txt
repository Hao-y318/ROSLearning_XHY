cmake_minimum_required(VERSION 3.10)
project(HelloWorld)
add_executable(app main.cpp src/HelloWorld.cpp)
include_directories(${PROJECT_SOURCE_DIR}/include)
