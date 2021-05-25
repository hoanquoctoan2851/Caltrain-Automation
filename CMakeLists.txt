cmake_minimum_required(VERSION 3.19)
project(Caltrain)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_C_FLAGS -pthread)



add_executable(Caltrain caltrain-runner.c)