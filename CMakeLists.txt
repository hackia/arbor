cmake_minimum_required(VERSION 3.26)

project(arbor)

add_executable(arbor main.cpp)

install(TARGETS arbor DESTINATION bin)

