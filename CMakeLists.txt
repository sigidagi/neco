cmake_minimum_required(VERSION 3.5)

project(neco)

add_compile_options(-Wall -Wextra)

add_library(neco neco.c)

add_subdirectory(examples)
