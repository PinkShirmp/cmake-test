cmake_minimum_required(VERSION 3.26.4)
project(hello)

include_directories(./include)


#set(SOURCES ./src/main.cpp ./src/math.cpp)

file(GLOB SOURCES "./src/*.cpp")

add_executable(${PROJECT_NAME} ${SOURCES})
