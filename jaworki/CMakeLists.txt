cmake_minimum_required(VERSION 3.29)
project(jaworki)

set(CMAKE_CXX_STANDARD 20)

add_executable(jaworki
        main.cpp
        matrix.cpp
        ode_solver.cpp
        ode_solver.h
        matrix.h
        opt_alg.cpp
        opt_alg.h
        solution.h
        solution.cpp
        lab_no.h)
