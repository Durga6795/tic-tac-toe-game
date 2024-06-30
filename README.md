# Tic Tac Toe Game

This is a simple console-based implementation of the classic Tic Tac Toe game written in Python. The game is played on a 3x3 grid where two players take turns to place their marks ("X" or "O") with the goal of being the first to get three in a row, column, or diagonal.

## How to Play
1. The game starts with an empty 3x3 grid displayed in the console.
2. Player 1 uses "O" and Player 2 uses "X".
3. Players take turns to enter a position (from 1 to 9) to place their mark on the grid. The positions correspond to the grid as follows:
   
     1 | 2 | 3
    -----------
     4 | 5 | 6
    -----------
     7 | 8 | 9

5. The game checks for the validity of the entered position and ensures it is not already occupied.
6. The game prints the updated grid after each turn.
7. The game checks for a winner after each move:
    - A player wins if they have three of their marks in a row, column, or diagonal.
8. If all positions are filled and there is no winner, the game ends in a tie.

## Running the Game

To run the game, execute the Python script in a console or terminal. You will be prompted to enter positions alternately for each player until there is a winner or a tie.

python tic_tac_toe.py

## Code Explanation

- `check(player, position)`: Validates the input position and updates the grid with the player's mark if valid.
- `winner(player)`: Checks the grid to determine if the current player has won the game.
- `printdict()`: Prints the current state of the grid.
- The game loop alternates turns between Player 1 and Player 2, checking for a winner after each move and ending in a tie if all positions are filled with no winner.

Enjoy playing Tic Tac Toe!
