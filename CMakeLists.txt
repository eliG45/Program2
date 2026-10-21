cmake_minimum_required(VERSION 4.3)
project(Program2)

set(CMAKE_CXX_STANDARD 20)

add_executable(Program2 main.cpp
        loadbalancer.cpp
        p2.cpp
        webserver.cpp
        loadbalancer.h
        request.h
        request.h
        loadbalancer.h)
