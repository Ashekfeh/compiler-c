cmake_minimum_required(VERSION 3.31)
project(compiler_c C)

set(CMAKE_C_STANDARD 23)

add_executable(compiler_c
        main.c
        chunk.c
        memory.c
        value.c
        debug.c
        vm.c
        scanner.c
        compiler.c
        object.c
        table.c
)
