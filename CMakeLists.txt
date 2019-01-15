cmake_minimum_required(VERSION 2.8)
project(hello_world)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
set(LIBRARY_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/lib)

include_directories(
${PROJECT_SOURCE_DIR}/include
)

add_executable(hello_world src/hello_world.cpp src/main.cpp)

