cmake_minimum_required(VERSION 3.17)
project(CreemUI)

include_directories(src/creem/src)

# CreemUI core
add_subdirectory(src/creem)



# Sandbox Project
add_subdirectory(src/sandbox)