cmake_minimum_required(VERSION 3.0.0)
project(GLAD VERSION 0.1.0)

include_directories(include)

add_library(
  GLAD SHARED
  src/glad.c
)