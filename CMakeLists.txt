cmake_minimum_required(VERSION 3.15)
project(algorithms)

set(CMAKE_CXX_STANDARD 14)

file(GLOB all_files "leetcode/*.cpp" "huawei/*.cpp" "data-structures/*.cpp")

add_executable(main main.cpp ${all_files})

add_executable(SortingAlgorithms algorithms/sorting-algorithms.cpp)
