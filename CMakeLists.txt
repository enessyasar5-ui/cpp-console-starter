cmake_minimum_required(VERSION 3.20)
project(cpp_console_starter LANGUAGES C CXX)

set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED ON)
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(c_hello main.c)
add_executable(cpp_hello main.cpp)
