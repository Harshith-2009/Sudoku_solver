# Sudoku_solver
Sudoku Solver in C++

This project is a Sudoku solver implemented using backtracking in C++.
It takes a 9x9 Sudoku grid as input (with -1 representing empty cells) and solves the puzzle if a solution exists.

Features:

Uses recursive backtracking to solve Sudoku

Validates rows, columns, and 3x3 sub-grids

Prints solved Sudoku if possible, otherwise outputs "No solution exists!"

How to Compile and Run:

Save the code in sudoku.cpp

Open terminal in the project folder

Compile the code using:
g++ sudoku.cpp -o sudoku

Run the program using:
./sudoku

Input Format:

Enter the Sudoku puzzle as a 9x9 grid

Use numbers 1–9 for filled cells

Use -1 for empty cells

Example Input:
5 3 -1 -1 7 -1 -1 -1 -1
6 -1 -1 1 9 5 -1 -1 -1
-1 9 8 -1 -1 -1 -1 6 -1
8 -1 -1 -1 6 -1 -1 -1 3
4 -1 -1 8 -1 3 -1 -1 1
7 -1 -1 -1 2 -1 -1 -1 6
-1 6 -1 -1 -1 -1 2 8 -1
-1 -1 -1 4 1 9 -1 -1 5
-1 -1 -1 -1 8 -1 -1 7 9

Output:
If a solution exists, the program prints the solved Sudoku. Example:

5 3 4 6 7 8 9 1 2
6 7 2 1 9 5 3 4 8
1 9 8 3 4 2 5 6 7
8 5 9 7 6 1 4 2 3
4 2 6 8 5 3 7 9 1
7 1 3 9 2 4 8 5 6
9 6 1 5 3 7 2 8 4
2 8 7 4 1 9 6 3 5
3 4 5 2 8 6 1 7 9

If no solution exists, the program prints:
No solution exists!

Concepts Used:

Backtracking algorithm

Recursion

2D vector handling in C++
