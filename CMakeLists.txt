cmake_minimum_required(VERSION 3.20)
project(my_second_cmake_project)
set(SOURCES "src/main.cpp" "src/Equilateral_Triangle.cpp" "src/Figure.cpp" "src/Isoscele_Triangle.cpp" "src/Parallelogram.cpp" "src/Quadrilateral.cpp" "src/Rectangle.cpp" "src/Rhombus.cpp" "src/Right_Triangle.cpp" "src/Square.cpp" "src/Triangle.cpp")
add_executable(my_second_cmake_project ${SOURCES} )