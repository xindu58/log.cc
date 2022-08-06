cmake_minimum_required(VERSION 3.22)
project(log_cc C)

set(CMAKE_C_STANDARD 11)

include_directories(src)
add_library(log STATIC src/log.c)
