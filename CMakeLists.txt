# Minimum CMake version
cmake_minimum_required(VERSION 3.30)

# Project definition
project(impakt VERSION 0.1)

# Set C++ standard attributes
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Set target
add_executable(${PROJECT_NAME} src/app/main.cpp)