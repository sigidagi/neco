cmake_minimum_required(VERSION 3.5)

project(neco)

add_compile_options(-Wall -Wextra -Wpedantic)

add_library(neco
    ${CMAKE_SOURCE_DIR}/neco.c
)

add_subdirectory(examples)
