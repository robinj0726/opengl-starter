cmake_minimum_required(VERSION 3.10)
project(opengl-starter)

set(GLEW_INCLUDE_DIRS "C:/Users/admin/Documents/GitHub/opengl-starter/common/glew-2.1.0/include")
set(GLEW_LIBRARIES_DIRS "C:/Users/admin/Documents/GitHub/opengl-starter/common/glew-2.1.0/lib/Release/x64")

set(GLFW_INCLUDE_DIRS "C:/Users/admin/Documents/GitHub/opengl-starter/common/glfw-3.3.8/include")
set(GLFW_LIBRARIES_DIRS "C:/Users/admin/Documents/GitHub/opengl-starter/common/glfw-3.3.8/lib-vc2019/")

include_directories(${GLEW_INCLUDE_DIRS} ${GLFW_INCLUDE_DIRS})
link_directories(${GLEW_LIBRARIES_DIRS} ${GLFW_LIBRARIES_DIRS})

add_subdirectory(lesson1)