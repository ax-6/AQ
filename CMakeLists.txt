# Copyright 2024 AQ author, All Rights Reserved.
# This program is licensed under the AQ License. You can find the AQ license in
# the root directory.

cmake_minimum_required(VERSION 3.10)
project(AQ C)
enable_testing()

include_directories(${PROJECT_SOURCE_DIR})

set(SOURCES ${CMAKE_CURRENT_SOURCE_DIR}/prototype/prototype.c)

add_executable(aq ${SOURCES})