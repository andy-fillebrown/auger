cmake_minimum_required(VERSION 3.14.2 FATAL_ERROR)

list(APPEND CMAKE_PREFIX_PATH "${CMAKE_SOURCE_DIR}/submodules")
find_package(af-cmake-qt-modules)

add_subdirectory(applications)
