cmake_minimum_required(VERSION 3.10)
project(opengl-starter)

set(GLEW_INCLUDE_DIRS "./common/glew-2.1.0/include")
set(GLEW_LIBRARIES_DIRS "./common/glew-2.1.0/lib/Release/x64")

set(GLFW_INCLUDE_DIRS "./common/glfw-3.3.8/include")
set(GLFW_LIBRARIES_DIRS "./common/glfw-3.3.8/lib-vc2017/")

set(SOIL2_INCLUDE_DIRS "./common/soil2/include")
set(SOIL2_LIBRARIES_DIRS "./common/soil2/lib/x64")

set(GLM_INCLUDE_DIRS "./common/glm-0.9.9.7/glm")
set(GLM_LIBRARIES_DIRS "./common/glm-0.9.9.7/glm/build/glm/Release")

include_directories(${GLEW_INCLUDE_DIRS} ${GLFW_INCLUDE_DIRS} ${SOIL2_INCLUDE_DIRS} ${GLM_INCLUDE_DIRS})
link_directories(${GLEW_LIBRARIES_DIRS} ${GLFW_LIBRARIES_DIRS} ${SOIL2_LIBRARIES_DIRS} ${GLM_LIBRARIES_DIRS})

add_subdirectory(Chapter01)
add_subdirectory(Chapter02)
add_subdirectory(Chapter03)