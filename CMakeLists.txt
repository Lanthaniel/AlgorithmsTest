cmake_minimum_required(VERSION 3.10.0)
project(AlgorithmsTest VERSION 0.1.0 LANGUAGES C CXX)

add_executable(AlgorithmsTest
    main.cpp
    Chapter4.cpp)

include(CTest)
enable_testing()

