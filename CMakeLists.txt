cmake_minimum_required(VERSION 3.0.0)
project(ohmsches_gesetz VERSION 0.1.0)

include(CTest)
enable_testing()

add_executable(ohmsches_gesetz main.cpp utils/formeln.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
