
cmake_minimum_required(VERSION 3.12 FATAL_ERROR)
list(APPEND CMAKE_PREFIX_PATH "${CMAKE_SOURCE_DIR}/submodules")
find_package(af-cmake-qt-modules)
add_subdirectory(applications)
add_subdirectory(libraries)
