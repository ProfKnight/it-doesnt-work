# Minimum version can be no higher than 3.5 as Ubuntu package management uses this version.
cmake_minimum_required(VERSION 3.5)

project (it-doesnt-work)

add_executable(it-doesnt-work src/main.cc)
target_compile_options(it-doesnt-work PRIVATE -Wall -O2)
include_directories(include/)
