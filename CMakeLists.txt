cmake_minimum_required(VERSION 3.26)

project(arbor)
set(CMAKE_CXX_STANDARD 26)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
add_compile_options(-Werror -Wextra -pedantic -ansi)
add_executable(arbor main.cpp)

install(TARGETS arbor DESTINATION bin)

