cmake_minimum_required(VERSION 3.6)
project(fiddle)

set(CMAKE_CXX_STANDARD 14)

add_library(fiddle src/fiddle/fiddle.cpp src/fiddle/fiddle.h)
