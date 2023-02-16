cmake_minimum_required(VERSION 3.24)

project(DesignPatterns
    VERSION 0.0.1
    DESCRIPTION "Learning Design Patterns C++"
    LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(factoryMethod factoryMethod.cxx)