cmake_minimum_required(VERSION 3.11)

project(glad C)

add_library(glad src/glad.c)
target_include_directories(glad PUBLIC include)



