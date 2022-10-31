cmake_minimum_required(VERSION 3.10)

project(Homework_3_11_3)

set(CMAKE_WINDOWS_EXPORT_ALL_SYMBOLS ON)
add_library(Leaver SHARED Leaver.h Leaver.cpp)
add_executable(Homework_3_11_3 Homework_3_11_3.cpp)
target_link_libraries(Homework_3_11_3 Leaver)