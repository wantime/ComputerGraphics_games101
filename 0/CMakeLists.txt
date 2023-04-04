cmake_minimum_required (VERSION 2.8.11)
project (test)

find_package(Eigen3 REQUIRED)
include_directories(EIGEN3_INCLUDE_DIR)

add_executable (test main.cpp)
