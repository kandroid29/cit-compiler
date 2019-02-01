cmake_minimum_required(VERSION 3.13)
project(cit_compiler C)

set(CMAKE_C_STANDARD 11)

add_executable(cit_compiler main.c scanner.c scanner.h)