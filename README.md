# sudoku_linear_programming_solver

## A web-based sudoku solver utilizing linear programming through the glpk.js libary.

1. Attaching the "sudoku__board" class to an empty div and calling the setGame() function automatically creates the board.
2. Calling ResetBoard() resets the board to  a random one from the provided board list
3. Calling clearBoard() empties out all entries in the board
4. Calling Solver() solves the board and returns a valid assignment if one exists 

The solver expects an array describing the rows of the board using '-' for empty cells and 1-9 for the numbers.

