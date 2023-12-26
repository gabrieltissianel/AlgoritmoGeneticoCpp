cmake_minimum_required(VERSION 3.27)
project(AlgoritmoGenetico)

set(CMAKE_CXX_STANDARD 17)

add_executable(AlgoritmoGenetico main.cpp
        Individuo.cpp
        Individuo.h)
