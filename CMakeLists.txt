cmake_minimum_required(VERSION 3.16)

project(WoWing)

add_subdirectory (dep)
add_subdirectory (src)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)
