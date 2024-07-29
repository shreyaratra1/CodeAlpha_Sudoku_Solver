# CodeAlpha_Sudoku_Solver
# Name-Shreya Ratra 
# Company-CodeAlpha 
# Student ID-CA/JL1/20260
# Domain-C++ Programming 
# Duration- 15TH July TO 15TH August 2024
#
# Overview of the Project-
# Project-
C++ program that act as a Sudoku Solver
# Objective-
The objective of this project is to build a program that act as a Sudoku Solver. Write a program that solves Sudoku puzzles. Implement an algorithm to solve puzzles of varying difficulty levels. You can also create a graphical user interface (GUI) for user interaction.
#
# Key Objectives-
Grid Initialization: The grid array represents the Sudoku puzzle. Empty cells are represented by zeros.
# 
Helper Functions:
isPresentInCol(int col, int num): Checks if num is present in the specified column.
isPresentInRow(int row, int num): Checks if num is present in the specified row.
isPresentInBox(int boxStartRow, int boxStartCol, int num): Checks if num is present in the 3x3 box starting at (boxStartRow, boxStartCol).
#
sudokuGrid(): Prints the Sudoku grid.
findEmptyPlace(int &row, int &col): Finds the next empty cell in the grid.
isValidPlace(int row, int col, int num): Checks if placing num in the specified cell is valid.
#
Solving Function:
solveSudoku(): The main recursive function that uses backtracking to solve the puzzle. It places numbers in empty cells, and if a placement leads to a solution, it returns true. If not, it backtracks by removing the number and trying the next possible number.
#
Main Function: The entry point of the program, which calls solveSudoku() and prints the solution if one exists, otherwise indicates that no solution exists.
Key Objective: The main goal of the program is to fill the empty cells in the Sudoku grid following the rules of Sudoku, which are:
Each number 1-9 must appear exactly once in each row, column, and 3x3 subgrid.
#
# Technologies Used:
Programming Language: C++
The entire program is written in C++, a versatile and powerful programming language known for its performance and extensive use in system/software development, game development, real-time simulations, and more.

Backtracking Algorithm:
The primary algorithmic approach used in this program is backtracking, a systematic method for solving problems by trying out various possibilities and abandoning them if they are not feasible solutions (i.e., backtracking). In this case, it's used to fill in the Sudoku grid by placing numbers sequentially, checking if they fit, and backtracking if they lead to an incorrect solution.

Recursion:
The solveSudoku() function uses recursion, a technique where a function calls itself to solve subproblems. This is typical in backtracking algorithms to explore different possibilities in a problem space.
 
Standard Input/Output (I/O):
The program uses standard I/O streams from the C++ standard library (iostream) for outputting the Sudoku grid and results to the console.

Array Manipulation:
The Sudoku grid is represented using a 2D array (int grid[N][N]), a fundamental data structure in C++ for storing data in rows and columns.

Logical Validation:
The program includes several helper functions (isPresentInCol, isPresentInRow, isPresentInBox, isValidPlace) that perform logical checks to ensure that the numbers being placed in the grid adhere to the rules of Sudoku.
#
# Output-
![Screenshot (43)](https://github.com/user-attachments/assets/dfc3d148-a3b7-4192-9b3c-e778e222e7c1)
