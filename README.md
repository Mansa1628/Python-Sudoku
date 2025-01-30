# Python-Sudoku

## Overview
This project is a **Sudoku Solver** that provides both a **Graphical User Interface (GUI)** and a **Backtracking Algorithm** to solve Sudoku puzzles. The GUI is built using **Pygame**, while the solving logic follows a **recursive backtracking approach**.

## Features
- **Interactive Sudoku Grid**: Users can input numbers manually.
- **Backtracking Algorithm**: Efficiently solves Sudoku puzzles.
- **GUI with Pygame**: Provides an intuitive interface for interaction.
- **Auto-Solve Functionality**: Allows users to watch the puzzle being solved in real time.

## Files in the Repository
- `GUI.py` - Implements the graphical interface using **Pygame**.
- `solver.py` - Contains the **backtracking algorithm** for solving Sudoku.
- `Intro.txt` - Brief explanation of the backtracking approach used.

## How It Works
1. **Grid Input**: Users can either input numbers manually or use the preloaded puzzle.
2. **Algorithm Execution**:
   - The solver picks an empty cell.
   - Tries numbers from **1 to 9**.
   - If a valid number is found, it moves to the next cell.
   - If an invalid placement occurs, it backtracks to the previous step.
3. **GUI Controls**:
   - Click on a cell to select it.
   - Use keyboard input to enter numbers.
   - Press `SPACE` to auto-solve the puzzle.
   - Press `DELETE` to clear an entry.

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sudoku-solver.git
   ```
2. Install dependencies:
   ```bash
   pip install pygame
   ```
3. Run the program:
   ```bash
   python GUI.py
   ```

## Dependencies
- Python 3.x
- Pygame
