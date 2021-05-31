cmake_minimum_required(VERSION 3.10)

project(CG_Lab6)

find_package(glbinding REQUIRED)
find_package(glfw3 3.3 REQUIRED)

add_executable(CG_Lab6 main.cpp)

target_link_libraries(CG_Lab6 glbinding::glbinding glbinding::glbinding-aux glfw)
