cmake_minimum_required(VERSION 3.17)

include(pico_sdk_import.cmake)

set(CMAKE_SYSTEM_NAME Linux)
set(CMAKE_SYSTEM_PROCESSOR arm)

project(ovenTempMeasure)

add_subdirectory(src)


