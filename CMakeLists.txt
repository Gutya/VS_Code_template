cmake_minimum_required(VERSION 3.21)

message("generator is set to ${CMAKE_GENERATOR}")
project(a)

include_directories(${PROJECT_SOURCE_DIR}/inc)

set(SOURCES src/main.cpp src/class.cpp)

add_executable(${PROJECT_NAME} ${SOURCES})