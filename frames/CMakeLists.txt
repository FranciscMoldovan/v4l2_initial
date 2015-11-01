set(CMAKE_C_FLAGS "-std=c99")
cmake_minimum_required(VERSION 2.8)
project( vee_for_l_two )
add_executable( main src/main.c )
target_link_libraries( main -ljpeg )

