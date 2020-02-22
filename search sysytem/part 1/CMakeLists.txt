cmake_minimum_required(VERSION 3.14)
project(correct)

set(CMAKE_CXX_STANDARD 17)

include_directories(.)

add_executable(correct
        iterator_range.h
        main.cpp
        parse.cpp
        parse.h
        profile_advanced.cpp
        profile_advanced.h
        search_server.cpp
        search_server.h)
