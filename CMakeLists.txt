cmake_minimum_required(VERSION 3.28.3)

project(Hello)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -Wall")

add_executable(hello helloworld.cpp)
