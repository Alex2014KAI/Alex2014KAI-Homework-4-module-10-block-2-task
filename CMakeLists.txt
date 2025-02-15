cmake_minimum_required(VERSION 3.20)
project(my_second_cmake_project)
set(SOURCES  "main.cpp"
			 "Equilateral_Triangle.cpp" 
			 "Figure.cpp" 
			 "Isoscele_Triangle.cpp" 
			 "Parallelogram.cpp" 
			 "Quadrilateral.cpp" 
			 "Rectangle.cpp" 
			 "Rhombus.cpp" 
			 "Right_Triangle.cpp" 
			 "Square.cpp" 
			 "Triangle.cpp")
set (HEADERS "Equilateral_Triangle.h" 
			 "Figure.h" 
			 "Isoscele_Triangle.h" 
			 "Parallelogram.h" 
			 "Quadrilateral.h" 
			 "Rectangle.h" 
			 "Rhombus.h" 
			 "Right_Triangle.h" 
			 "Square.h" 
			 "Triangle.h")
add_executable(my_second_cmake_project ${SOURCES} ${HEADERS})