cmake_minimum_required(VERSION 3.5)
project(Z80Emu)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES src/main.cpp)
add_executable(Z80Emu ${SOURCE_FILES})