cmake_minimum_required(VERSION 3.28)
project(glad)

set(CMAKE_C_STANDARD 17)

include_directories(glad/include)

add_library(glad glad/src/glad.c)
