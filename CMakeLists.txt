cmake_minimum_required(VERSION 3.15)
project(louvain)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(louvain
        src/main.cpp
        src/main.h)
