cmake_minimum_required(VERSION 3.4.0)

project(directory_test)

set(CMAKE_CXX_FLAGS "-std=c++11")

include_directories(include)

file(GLOB SOURCES "src/*.cpp")

add_executable(hello ${SOURCES})