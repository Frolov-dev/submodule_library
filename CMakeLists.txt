cmake_minimum_required(VERSION 3.15)

add_library(submodule_library
    src/math_operations.cpp
)

target_include_directories(submodule_library PUBLIC include)