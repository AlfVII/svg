cmake_minimum_required(VERSION 3.9)
project(SVG)

set(CMAKE_CXX_FLAGS "-lpthread -static-libgcc -static-libstdc++")
set(CMAKE_CXX_STANDARD 20)
set(SOURCES src/svg.hpp)
