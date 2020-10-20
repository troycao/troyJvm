cmake_minimum_required(VERSION 3.17)
project(troyJvm)

set(CMAKE_CXX_STANDARD 14)

add_executable(troyJvm main.cpp include/troy_jvm.cpp include/classloader.h)