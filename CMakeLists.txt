
set(GETOPTPP_INCLUDE ${CMAKE_CURRENT_SOURCE_DIR}/getoptpp PARENT_SCOPE)

include_directories(${CMAKE_CURRENT_SOURCE_DIR})

add_library(getoptpp STATIC src/getopt_pp.cpp)
