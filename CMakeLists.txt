cmake_minimum_required(VERSION 2.8)
project(lab2)

add_library(calc STATIC src/calculator.cpp src/calculator.h)
add_executable(out src/main.cpp)

target_link_libraries(out lab2)