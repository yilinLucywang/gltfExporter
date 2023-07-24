cmake_minimum_required(VERSION 3.25)
project(gltfExporter)

set(CMAKE_CXX_STANDARD 17)

add_executable(gltfExporter main.cpp MeshExporter.cpp MeshExporter.h)
