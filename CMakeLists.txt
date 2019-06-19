cmake_minimum_required(VERSION 3.0.0)

# make sure to include external project module of cmake
include(ExternalProject)

# set the project name
set(PROJECT_NAME "embedded-protobuf")

# add cmake dir
add_subdirectory(${CMAKE_SOURCE_DIR}/cmake)
