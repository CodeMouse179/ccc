cmake_minimum_required(VERSION 3.10)

project(ccc)

set(CMAKE_CXX_STANDARD 11)

add_executable(ccc
    ./src/String.hpp
    ./src/ccc.hpp
    ./src/main.cpp
)