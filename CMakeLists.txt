cmake_minimum_required(VERSION 3.0)

project(text-summer)

add_executable(text-summer main.cpp)

install(TARGETS text-summer RUNTIME DESTINATION bin)
