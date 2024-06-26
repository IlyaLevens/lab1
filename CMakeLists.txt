cmake_minimum_required(VERSION 3.27)
project(laboratory1 C)

set(CMAKE_C_STANDARD 11)

add_executable(laboratory1 main.c
        UI.h
        UI.c
        DynamicArray.c
        DynamicArray.h
        int_functions.h
        int_functions.h
        int_functions.c
        str_functions.h
        str_functions.c
        tests.h
        tests.c)
