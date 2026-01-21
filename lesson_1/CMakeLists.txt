cmake_minimum_required(VERSION 3.20)

project(cpp_hero_lesson1 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(cpp_hero
    src/main.cpp
    src/math.cpp
)

target_include_directories(cpp_hero
    PRIVATE
        include
)
