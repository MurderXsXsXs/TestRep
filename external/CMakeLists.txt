cmake_minimum_required(VERSION 3.29 FATAL_ERROR)

project(GLAD)

add_library(GLAD STATIC include/glad/glad.h src/glad.c)
target_include_directories(glad PUBLIC include/)