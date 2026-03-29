cmake_minimum_required(VERSION 4.3.0)
project(LearningOpenGL)

find_package(OpenGL REQUIRED)

add_executable(${PROJECT_NAME} 
    src/main.cpp
    src/glad.c
)

target_link_libraries(${PROJECT_NAME} glfw)
