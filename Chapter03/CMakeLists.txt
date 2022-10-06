add_executable(ch03_transformations Transformations/main.cpp)
target_link_libraries(ch03_transformations PRIVATE opengl32.lib glew32s.lib glfw3.lib soil2.lib glm_static.lib)
