cmake_minimum_required(VERSION 2.8)
project(BosonUSB)

set (CMAKE_CXX_STANDARD 11)

find_package(OpenCV REQUIRED)

add_executable(BosonUSB BosonUSB.cpp)
target_link_libraries(BosonUSB ${OpenCV_LIBRARIES})

