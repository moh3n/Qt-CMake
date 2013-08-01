cmake_minimum_required(VERSION 2.6)
project(qt_cmake)

find_package(Qt4 REQUIRED)
include(${QT_USE_FILE})

add_executable(qt_cmake WIN32 main.cpp)
target_link_libraries(qt_cmake ${QT_LIBRARIES})
