cmake_minimum_required(VERSION 3.10)
set(CXX_STANDARD 11)
set(C_STANDARD 11)
project(TinyRenderer)

set(SRC 
    tgaimage/tgaimage.h
    tgaimage/tgaimage.cpp
    main.cpp
)

add_executable(tinyrenderer ${SRC})