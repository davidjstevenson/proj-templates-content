cmake_minimum_required(VERSION 3.2)
project(MyProjectExe CXX)

include(sources.cmake)
add_executable(MyProject ${SOURCES})
target_link_libraries(MyProject )
