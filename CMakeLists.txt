cmake_minimum_required(VERSION 3.16)
project(Cproject C)

set(CMAKE_C_STANDARD 90)

add_executable(Cproject
        second_pass.c assembler.c "first_pass.c" "first pass.h" "assembler_data_types.c" "assembler data types.h" errors.c errors.h "line_analyzer.c" "line analyzer.h" "symbol_table.c" "symbol table.h" translator.c translator.h "in_out_tools.c" "in_out_tools.h")
