# N-Queens Solver

This project provides a Python implementation of the N-Queens problem, which is a classic combinatorial problem where N queens must be placed on an N×N chessboard such that no two queens attack each other.

## Features
- Solves the N-Queens problem using a backtracking algorithm.
- Displays all possible solutions for a given board size.
- Command-line interface for user input.

## Requirements
- Python 3.x

## Usage
1. Run the script:
   ```sh
   python script.py
   ```
2. Enter the number of queens (N) when prompted.
3. The program will display all valid solutions.

## Code Overview
- `is_position_safe(board, row, col, n)`: Checks if a queen can be placed at a given position.
- `place_queens(board, row, n, solutions)`: Uses backtracking to place queens.
- `solve_n_queens(n)`: Solves the N-Queens problem and returns a list of solutions.
- `main()`: Handles user input and prints results.

## Example Output
```
Enter the number of queens (N): 4

Total solutions for 4-Queens: 2
Solution 1:
.Q..
...Q
Q...
..Q.

Solution 2:
..Q.
Q...
...Q
.Q..
```
