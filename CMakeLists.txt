cmake_minimum_required(VERSION 4.0)
project(ray_tracing_in_one_weekend)

set(CMAKE_CXX_STANDARD 20)

set(CMAKE_EXE_LINKER_FLAGS "-static")

add_executable(ray_tracing_in_one_weekend main.cpp)
