cmake_minimum_required(VERSION 3.17)
project(CREEM VERSION 0.1)


add_library(creem STATIC src/creem.cpp src/creem.h)
target_compile_definitions(creem PRIVATE CREEM_INTERNAL)
target_precompile_headers(creem PRIVATE src/pch.h)