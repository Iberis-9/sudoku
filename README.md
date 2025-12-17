## 🧩 Sudoku Game (Python)

<br>

A terminal-based Sudoku game implemented in a Jupyter notebook using pure Python functions.

This project was built as a learning exercise to explore functional programming concepts in Python, including function decomposition, state handling, validation logic, and control flow — without relying on external libraries or frameworks.

<br>

## 🧩 Project overview

<br>

The notebook walks through building a complete Sudoku game step by step:

- Creating and displaying a Sudoku board
- Manually defining a solvable puzzle and its solution
- Handling user input and validating moves
- Enforcing Sudoku rules (rows, columns, sub-grids)
- Detecting game completion
- Allowing replay once the puzzle is solved
 
All game logic is implemented using small, focused functions that each handle a single responsibility.

<br>

## 🧩 Tools
<br>

This notebook implements a Sudoku game using user-defined Python functions. The focus on functional decomposition means Python alone is sufficient, with no external libraries required.
<br>

| Tool                  | Purpose                               |
| --------------------- | ------------------------------------- |
| Python                | Core language                         |
| Jupyter Notebook      | Interactive development and execution |
| Standard library only | No external dependencies              |

<br>

## 🧩 How it works (high level)

<br>

- The board is represented as a nested list
- A separate solution board is used for validation
- User input is handled via standard input
- Each move is checked for correctness before being placed
- The game ends when the board contains no empty cells


<br>

## 🧩 Running the game

<br>

1. Open the notebook in Jupyter

2. Run all cells in order

3. Follow the prompts in the output cell to play

4. The game runs entirely in the notebook environment using terminal-style input and output.

<br>

## 🧩 Possible extensions

<br>

- Difficulty levels with different board templates
- Randomised puzzle generation
- Input validation for illegal placements beyond solution matching
- Refactoring into a standalone Python script or package
- Simple text or graphical interface

