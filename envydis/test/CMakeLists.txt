project(ENVYTOOLS C)
cmake_minimum_required(VERSION 3.5)

add_test(fuc_smoke ${CMAKE_CURRENT_SOURCE_DIR}/fuc_smoke ${CMAKE_CURRENT_BINARY_DIR}/../envydis)
