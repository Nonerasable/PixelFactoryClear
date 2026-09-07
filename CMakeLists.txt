cmake_minimum_required(VERSION 3.21)

project(PixelFactory LANGUAGES CXX)

add_executable(PixelFactory
    src/main.cpp
)

set_target_properties(PixelFactory PROPERTIES
    CXX_STANDARD 23
    CXX_STANDARD_REQUIRED ON
    CXX_EXTENSIONS OFF
)