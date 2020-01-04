# CMake file for CuttingStockProblem.
cmake_minimum_required (VERSION 3.8)

add_executable (CuttingStockProblem "bool.h" "column.h" "column.c" 
"cutting_stock.h" "cutting_stock.c" "main.c"  "matrix.h" "matrix.c"
"order.h" "order.c" "utils.h" "utils.c")

# Link GNU GLPK library
target_link_libraries(CuttingStockProblem "glpk_4_65.lib")
