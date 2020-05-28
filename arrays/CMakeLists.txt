cmake_minimum_required(VERSION 3.4.1)

set(CMAKE_CXX_STANDARD 11)
add_definitions(-Werror) # stop compile on warning

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O3")

set(SOURCES main.cpp)
add_executable(arrays ${SOURCES})
