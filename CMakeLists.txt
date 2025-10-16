cmake_minimum_required(VERSION 4.0)
project(5_5)

set(CMAKE_CXX_STANDARD 20)

add_executable(5_5 5.5.cpp
        functions.h
        functions.cpp
        tests/UnitTest.cpp)
