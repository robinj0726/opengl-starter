add_executable(ch01_glfw main.cpp)
target_link_libraries(ch01_glfw PRIVATE opengl32.lib glew32s.lib glfw3.lib)