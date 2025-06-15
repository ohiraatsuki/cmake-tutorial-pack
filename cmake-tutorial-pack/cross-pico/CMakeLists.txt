cmake_minimum_required(VERSION 3.13)
project(PicoCross)
set(CMAKE_TOOLCHAIN_FILE ${CMAKE_SOURCE_DIR}/toolchain-pico.cmake)
add_executable(pico_app src/main.cpp)