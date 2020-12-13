cmake_minimum_required(VERSION 3.17)
project(processpool)

set(CMAKE_CXX_STANDARD 11)

add_executable(processpool main.cpp lib/processpool.h)