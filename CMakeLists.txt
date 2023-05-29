cmake_minimum_required(VERSION 3.1)
project(hole_fixer)

include_directories(libigl/ libigl/eigen/)
add_executable(hole_fixer main.cpp)

set (CMAKE_CXX_STANDARD 11)
target_link_libraries(hole_fixer pthread)

