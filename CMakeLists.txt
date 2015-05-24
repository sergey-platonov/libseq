project(libseq)
cmake_minimum_required(VERSION 2.8)
set(CMAKE_CXX_FLAGS "-std=c++11 ${CMAKE_CXX_FLAGS}")
aux_source_directory(. SRC_LIST)
add_library(${PROJECT_NAME} ${SRC_LIST})

