cmake_minimum_required(VERSION 3.20)
project(cpp_project)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(cpp_project
        boss.cpp
        boss.h
        employee.cpp
        employee.h
        manager.cpp
        manager.h
        worker.h
        workerManager.cpp
        workerManager.h
        workerManger.cpp
        基于多态的职工管理系统.cpp
        职工管理系统.cpp)
