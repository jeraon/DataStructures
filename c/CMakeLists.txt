cmake_minimum_required(VERSION 3.14)
project(c C)

set(CMAKE_C_STANDARD 11)

add_executable(c main.c linkedlist/linkedlist.h linkedlist/linkedlist.c)