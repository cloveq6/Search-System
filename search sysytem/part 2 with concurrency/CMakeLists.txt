cmake_minimum_required(VERSION 3.14)
project(correct_2)

set(CMAKE_CXX_STANDARD 17)

include_directories(.)

add_executable(correct_2
        iterator_range.h
        main.cpp
        parse.cpp
        parse.h
        search_server.cpp
        search_server.h
        synchronized.h
        test_runner.h)
