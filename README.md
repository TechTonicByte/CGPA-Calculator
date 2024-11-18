# CGPA-Calculator
CGPA calculator in C++

# CGPA Calculator in C++

This project is a simple CGPA calculator developed in C++. The program takes the number of courses, grades, and credit hours for each course as input, and calculates the CGPA based on the provided data.

## Features
- Input the number of courses.
- Enter the grade and corresponding credit hours for each course.
- Calculate CGPA based on the grades and credits.
- Supports grades in standard letter format (A, B, C, etc.) and converts them to the appropriate grade points.

## How it Works
1. The user is prompted to input the number of courses.
2. For each course, the user enters:
   - The grade (A, B, C, etc.).
   - The credit hours of the course.
3. The program computes the total grade points and divides it by the total credit hours to output the CGPA.

### Grade Points Mapping:
| Grade | Grade Points |
|-------|--------------|
| A+    | 4.0          |
| A     | 4.0          |
| B+    | 3.5          |
| B     | 3.0          |
| C+    | 2.5          |
| C     | 2.0          |
| D     | 1.0          |
| F     | 0.0          |

## Requirements
- C++ Compiler (e.g., g++, clang++)
- Basic understanding of C++ programming

## How to Run

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/cgpa-calculator-cpp.git
