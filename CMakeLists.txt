cmake_minimum_required(VERSION 3.22.1)

project(CMT)

add_executable(${PROJECT_NAME} main.cpp)

add_subdirectory(lib/mult)

target_link_libraries(${PROJECT_NAME} mult)
