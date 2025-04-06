cmake_minimum_required(VERSION 3.20.0)
project(hello_world)

add_executable(${PROJECT_NAME} main.c)

target_link_libraries(${PROJECT_NAME} zephyr)



