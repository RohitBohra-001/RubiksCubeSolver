cmake_minimum_required(VERSION 3.28)
project(RubiksCubeSolver)

set(CMAKE_CXX_STANDARD 17)

add_executable(RubiksCubeSolver main.cpp
        RubiksCube.cpp
        RubiksCube.h
        RubiksCube3dArray.cpp
        RubiksCube1dArray.cpp
        RubiksCubeBitboard.cpp
)
