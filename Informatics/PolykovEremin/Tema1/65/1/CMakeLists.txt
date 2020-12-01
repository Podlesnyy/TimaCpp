cmake_minimum_required(VERSION 3.17)
project(1)

set(CMAKE_CXX_STANDARD 17)

IF (${CMAKE_BUILD_TYPE} STREQUAL "Debug")
    add_definitions(-DDEBUG)
ENDIF()

add_executable(1 main.cpp)