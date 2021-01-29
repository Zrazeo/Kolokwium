cmake_minimum_required(VERSION 3.10)
project(myProgram)
file(GLOB SOURCES *.cpp)
add_executable(myProgram ${SOURCES})

