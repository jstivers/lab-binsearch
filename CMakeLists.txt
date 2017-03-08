cmake_minimum_required(VERSION 3.6)
project(lab_binsearch)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        binsearch.cpp
        sorted_data.in
        unsorted_data.in)

add_executable(lab_binsearch ${SOURCE_FILES})