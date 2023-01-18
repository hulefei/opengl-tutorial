cmake_minimum_required(VERSION 3.24)
project(opengl_tutorial)

set(CMAKE_CXX_STANDARD 17)

include_directories(Libraries/include)
link_directories(Libraries/lib)

add_subdirectory(tutorial00_install)
add_subdirectory(tutorial01_create_window)
add_subdirectory(tutorial02_triangle)
# Tutorial 1
#add_executable(tutorial00_install tutorial00_install/tutorial00.cpp)

# Tutorial 1
#add_executable(tutorial01_create_window tutorial01_create_window/tutorial01.cpp tutorial01_create_window/glad.c)
#target_link_libraries(tutorial01_create_window glfw3)

#add_executable(opengl_tutorial main.cpp tutorial00_install/tutorial00.cpp)
