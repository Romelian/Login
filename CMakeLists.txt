cmake_minimum_required(VERSION 3.22.1)

# set the project name
project(PROJECT_NAME)

set(CMAKE_CXX_STANDARD 20)
add_compile_options(-Wall -Wextra -Wpedantic -Werror)

add_subdirectory(src)