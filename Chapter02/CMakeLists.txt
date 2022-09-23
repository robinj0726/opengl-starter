add_executable(ch02_triangle Triangle/main.cpp)
target_link_libraries(ch02_triangle PRIVATE opengl32.lib glew32s.lib glfw3.lib)

add_executable(ch02_shaders Shaders/main.cpp)
target_link_libraries(ch02_shaders PRIVATE opengl32.lib glew32s.lib glfw3.lib)