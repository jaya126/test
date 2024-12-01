cmake_minimum_required(VERSION 3.10)

# Set the project name
project(HelloWorld)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 11)

# Include directories
include_directories(include)

# Add the source files
add_executable(HelloWorld src/main.cpp src/HelloWorld.cpp)
