cmake_minimum_required(VERSION 3.14...3.23)
project(otus_patterns)

set(CMAKE_CXX_STANDARD 20)

add_subdirectory(src)

include(CTest)
if(BUILD_TESTING)
    add_subdirectory(tests)
endif()
