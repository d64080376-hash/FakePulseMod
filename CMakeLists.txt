cmake_minimum_required(VERSION 3.25)
include(FetchContent)

project(FakePulseMod VERSION 1.0.0 LANGUAGES CXX)

add_library(${PROJECT_NAME} SHARED
    src/main.cpp
)

setup_geode_mod(${PROJECT_NAME})
