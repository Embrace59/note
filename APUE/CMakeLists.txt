cmake_minimum_required(VERSION 3.13)
project(node)

set(CMAKE_CXX_STANDARD 14)

add_executable(myls myls.cpp)
add_executable(out out.cpp)
add_executable(a a.cpp)
add_executable(file file.cpp)
add_executable(3-4 3-4.cpp)
add_executable(4-1 4-1.cpp)
add_executable(4-5 4-5.cpp)
add_executable(8-1 8-1.cpp)

target_link_libraries(myls apue)