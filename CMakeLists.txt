project(FPCPP)
cmake_minimum_required(VERSION 2.8)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

set_property(GLOBAL PROPERTY USE_FOLDERS ON)

include_directories(common)
add_subdirectory(chapter-01)
add_subdirectory(chapter-02)
add_subdirectory(chapter-03)
add_subdirectory(chapter-04)

