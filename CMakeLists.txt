cmake_minimum_required(VERSION 3.25)
project(2023_05)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(2023_05
        cuda_utils.h
        first_add.cu
        multiple.cu
        naive.cu
        sequential.cu
        stride.cu
        timer.c
        timer.h
        transpose.cu
        unroll.cu)
