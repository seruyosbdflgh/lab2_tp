cmake_minimum_required(VERSION 4.2.0)

project(lab2)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

include_directories(${CMAKE_CURRENT_SOURCE_DIR})

set(SOURCES
    main.cpp
    check.cpp
    container.cpp
    student.cpp
    sentense_filter.cpp
)

add_executable(${PROJECT_NAME} ${SOURCES})