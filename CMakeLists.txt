cmake_minimum_required(VERSION 2.8)
add_executable(echo main.c)
target_link_libraries(echo uring)