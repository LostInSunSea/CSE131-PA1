cmake_minimum_required(VERSION 3.4)
project(CSE131_PA1)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    errors.cc
    errors.h
    location.h
    main.cc
    scanner.h
    utility.cc
    utility.h)

add_executable(CSE131_PA1 ${SOURCE_FILES})