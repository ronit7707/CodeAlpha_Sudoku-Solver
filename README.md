# 🧩 Sudoku Solver (C++)
A console-based Sudoku Solver implemented in C++ using the Backtracking Algorithm. The program represents the Sudoku grid as a 2D array and fills in the empty cells by validating Sudoku constraints (rows, columns, and 3x3 subgrids).

# ✨ Features
Solve any standard 9x9 Sudoku Puzzle.

~ Uses Backtracking Algorithm for solving.

~ Efficient and fast recursive approach.

~ Clean and modular C++ code structure.

~ Simple Console Input/Output Interface.

# 🚀 Getting Started
Prerequisites

~ C++ Compiler (GCC / MinGW / MSVC / Clang)

~ Visual Studio Code / Code::Blocks / DevC++ or any C++ IDE.

~ Basic knowledge of C++ and recursion.

# 🖥️ Usage
1.The program expects a 9x9 Sudoku grid as input.

2.Enter 0 for empty cells.

3.The program will output the solved Sudoku grid if a solution exists.

# 🛠️ How It Works
1.The grid is represented as a 2D array.

2.The program searches for empty cells (value 0).

3.For each empty cell, it tries numbers from 1 to 9:

--> Checks if placing the number violates Sudoku rules:

--> No duplicate in current row.

--> No duplicate in current column.

--> No duplicate in current 3x3 subgrid.

4.If valid, it proceeds recursively.

5.If no number fits, it backtracks.

6.Stops when the puzzle is solved.

# 🧱 Future Enhancements
~ Add a Graphical User Interface (GUI).

~ Visual step-by-step animation of the solving process.

~ Support for Sudoku puzzle generation.

~ Timer to show solving time statistics.

# 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

# 🙌 Acknowledgements
--> C++ Backtracking Tutorials.

--> Sudoku Problem Examples from sudoku.com.

📧 Contact
For queries and suggestions:

Ronit Kumar — ronitsingh81025@gmail.com

GitHub: ronit7707
