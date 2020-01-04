# CMake file for CuttingStockProblem.
cmake_minimum_required (VERSION 3.8)

project ("CuttingStockProblem")

link_directories("..\\glpk-4.65\\w32")
include_directories("..\\glpk-4.65\\src")

add_subdirectory ("src")