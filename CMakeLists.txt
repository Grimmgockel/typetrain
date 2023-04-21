cmake_minimum_required(VERSION 3.10)
project(my_project)

set(CMAKE_CXX_STANDARD 11)

# Add the raylib library
add_subdirectory(raylib/)

# Add your project files
add_executable(typetrain main.cpp)

# Link your project with the raylib library
target_link_libraries(typetrain raylib)

