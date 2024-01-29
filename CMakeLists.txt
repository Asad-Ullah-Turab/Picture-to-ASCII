cmake_minimum_required(VERSION 3.0.0)
project(PICTURE-TO-ASCII VERSION 0.1.0 LANGUAGES C CXX)

include(CTest)
enable_testing()

add_executable(PICTURE-TO-ASCII main.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
