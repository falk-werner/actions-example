cmake_minimum_required (VERSION 3.10)
project(actions-example VERSION 1.0.0 HOMEPAGE_URL "https://github.com/falk-werner/actions-example")

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS ON)

add_executable(actions-example src/main.cpp)
install(TARGETS actions-example)

