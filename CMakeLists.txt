cmake_minimum_required(VERSION 3.2)
set(CMAKE_CXX_COMPILER "/usr/bin/clang++")

project(inih)

add_library(inih
        ini.c
        ini.h
        cpp/INIReader.cpp
        cpp/INIReader.h
)
