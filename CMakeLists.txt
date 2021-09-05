cmake_minimum_required(VERSION 3.14)

project(TestProject VERSION 1.0)


set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED True)
set(CMAKE_EXPORT_COMPILE_COMMANDS on)

add_subdirectory(lib)
add_subdirectory(src)
add_subdirectory(include)

