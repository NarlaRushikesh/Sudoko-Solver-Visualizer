# 🧩 Sudoku Solver Visualizer (Java + Swing)

A visual and interactive Sudoku solver written in Java. This project uses the backtracking algorithm to solve Sudoku puzzles and visualizes the process using a graphical user interface (GUI) built with Java Swing.

## 📌 Features

- 🧠 Recursive backtracking algorithm
- 🖥️ Real-time solving visualization using Java Swing
- 📋 Preloaded Sudoku puzzles
- 🎨 Color-coded cells for solved and backtracked steps

## 📁 Files

- `SudokuSolver.java`: Main application file that contains:
  - Board initialization
  - Recursive solving logic
  - Sudoku visualizer using Swing components

## 🧠 How it Works

- The solver uses the standard backtracking approach to fill in empty cells.
- The UI updates live as the algorithm attempts to solve the board.
- Cyan = valid move  
  Red = backtrack step  
  Gray = original numbers

## 🚀 How to Run

1. Make sure you have Java installed.  
   You can check using:
   ```bash
   java -version
