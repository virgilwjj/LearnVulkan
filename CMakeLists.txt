cmake_minimum_required(VERSION 3.0.0)
project(LearnVulkan)

add_subdirectory(external/glfw)

include_directories(external/glm)

add_subdirectory(demos/00_HelloWindow)
add_subdirectory(demos/01_HelloTriangle)
