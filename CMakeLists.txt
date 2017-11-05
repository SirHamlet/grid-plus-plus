cmake_minimum_required(VERSION 3.9)

project(grid-plus-plus)

set(CMAKE_CXX_STANDARD 17)

add_subdirectory(fast-cpp-csv-parser)

add_executable(grid-plus-plus main.cpp)