cmake_minimum_required(VERSION 3.12)
project(p1 C)

set(CMAKE_C_STANDARD 11)

add_executable(p1
        decode.c
        decode.i)
