#cmake_minimum_required (VERSION 2.6)
#project (snark)

#include_directories("${GMT_INCLUDE_DIR}")
#include_directories("${SODIUM_INCLUDE_DIR}")
set( CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -g -DBINARY_OUTPUT -DNO_PT_COMPRESSION" )
include_directories ("src")
add_subdirectory ("src") 
