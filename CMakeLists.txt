cmake_minimum_required(VERSION 3.16)

project(hello_RobotMaster_Cmake LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(hello_robotmaster src/hello.cpp)

target_compile_options(hello_robotmaster PRIVATE -Wall -Wextra)