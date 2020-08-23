cmake_minimum_required(VERSION 3.15)
project(calander_merger)

set(CMAKE_CXX_STANDARD 14)
include_directories(/usr/local/include/lest)

add_executable(calander_merger main.cpp)