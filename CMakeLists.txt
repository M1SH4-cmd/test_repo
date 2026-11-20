cmake_minimum_required(VERSION 4.1)
project(WinKill LANGUAGES CXX)
set(CMAKE_CXX_STANDARD 20)

add_executable(${PROJECT_NAME}
        main.cpp
        og.h
)
