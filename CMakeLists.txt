cmake_minimum_required(VERSION 3.25)
project(untitled C)

set(CMAKE_C_STANDARD 11)

add_executable(untitled main.c libs/data_structures/vector/vector.c libs/data_structures/vector/vector.h)
