cmake_minimum_required(VERSION 3.0)
project(webbench)

add_executable(${PROJECT_NAME} webbench.c socket.c socket.h)
