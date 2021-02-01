cmake_minimum_required(VERSION 3.10)
project(dyad C)
add_library(dyad src/dyad.c)
target_include_directories(dyad PUBLIC src)
