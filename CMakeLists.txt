
cmake_minimum_required(VERSION 2.8.4)

project(PETULANT_COMPUTING_MACHINE)

set( EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR}/bin )

add_executable( hello_world
                ${PROJECT_SOURCE_DIR}/src/0001_hello_world.cpp )
