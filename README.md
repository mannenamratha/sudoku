

# Sudoku Game

## Overview

This is a simple Sudoku game implemented using the Pygame library in Python. The game allows users to solve Sudoku puzzles, interact with the grid using keyboard and mouse inputs, and provides feedback for errors and completion.

## Features

- **Sudoku Grid Display**: Displays a Sudoku grid with numbers.
- **Highlight Box**: Highlights the current cell selected.
- **Input Handling**: Allows users to input numbers using keyboard keys.
- **Puzzle Solving**: Includes a solver that can automatically fill in the grid.
- **Error Messages**: Provides feedback when invalid values are entered.
- **Reset and Load Puzzle**: Options to reset the puzzle or load a default Sudoku puzzle.

## Requirements

- Python 3.x
- Pygame library

## Installation

1. **Install Python**: Make sure you have Python 3.x installed on your machine.

2. **Install Pygame**: Install the Pygame library using pip:
   ```bash
   pip install pygame
   ```

3. **Clone the Repository** (if applicable):
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

## How to Run

1. Save the provided code into a file named `sudoku_game.py`.

2. Run the game using Python:
   ```bash
   python sudoku_game.py
   ```

## Controls

- **Mouse**: Click on cells to select them.
- **Arrow Keys**: Move the selection box up, down, left, or right.
- **Number Keys (1-9)**: Enter numbers into the selected cell.
- **Enter Key**: Trigger the Sudoku solver to automatically fill the grid.
- **R Key**: Reset the puzzle to a blank grid.
- **D Key**: Load a default Sudoku puzzle.

## Functionality

- **Highlight Box**: The currently selected cell is highlighted.
- **Fill Value**: Enter a number into the selected cell if it’s valid according to Sudoku rules.
- **Error Handling**: Displays an error message if an invalid number is entered.
- **Solve Game**: Automatically solves the puzzle and updates the grid. Provides feedback on whether the puzzle is solved or not.
- **Game Result**: Displays a message when the Sudoku puzzle is successfully solved.

## Code Structure

- **Initialization**: Sets up the Pygame window and initializes the game state.
- **Drawing Functions**: Functions to draw the Sudoku grid and numbers.
- **Input Handling**: Functions to handle user input from the keyboard and mouse.
- **Game Logic**: Functions for validating values, solving the Sudoku puzzle, and managing game state.

## Example

1. **Start the Game**: Run the script and the Sudoku grid will be displayed.
2. **Select a Cell**: Click on a cell to select it.
3. **Enter Numbers**: Use the number keys to enter a value into the selected cell.
4. **Solve Puzzle**: Press Enter to let the game solve the puzzle.
5. **Handle Errors**: If an invalid number is entered, an error message will appear.

## Troubleshooting

- **Game Not Starting**: Ensure Python and Pygame are correctly installed.
- **Invalid Input Handling**: Check the console for error messages or debug the code for input validation issues.


