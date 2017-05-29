cmake_minimum_required(VERSION 3.7)
project(CarND_Localization_Lab)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        src/help_functions.h
        src/main.cpp
        src/map.h
        src/measurement_package.h
        src/bayesianFilter.cpp)

add_executable(CarND_Localization_Lab ${SOURCE_FILES})