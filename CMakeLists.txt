cmake_minimum_required(VERSION 3.28)
project(jwt_cpp_tut)

set(CMAKE_CXX_STANDARD 17)

find_package(jwt_cpp REQUIRED)

add_executable(jwt_cpp_tut main.cpp)
