# Tic Tac Toe Game

This is a simple implementation of the Tic Tac Toe game using Python in Jupyter Notebook.

## Game Rules

Tic Tac Toe is a two-player game played on a 3x3 grid. The players take turns marking their respective symbol (usually 'X' or 'O') on an empty cell. The first player to get three of their symbols in a row, column, or diagonal wins the game. If all cells are filled and no player has won, the game is a draw.

## Game Features

- Two players can play the game (offline and in one computer).
- The game board is displayed after each move.
- Players are prompted to enter their moves.
- The game automatically detects winning conditions and declares a winner.
- The game can be replayed multiple times.

## How to Run

1. Install Python and Jupyter Notebook if you haven't already.
2. Download or clone this repository.
3. Open the Jupyter Notebook file named `Tic Tac Toe.ipynb`.
4. Run each cell in the notebook to execute the code.
5. Follow the instructions in the notebook to play the game.

## Implementation Details

The game is implemented using Python and Jupyter Notebook. It uses a list to represent the game board and checks for winning conditions after each move. The game logic is implemented using functions.

## Sample Gameplay

Here's an example of how the game is played:

    Welcome to Tic Tac Toe!
    Please pick a marker 'X' or 'O': x
    Player1: X
    Player2: O

    Player1 will go first.

    7 | 8 | 9
    -------------
    4 | 5 | 6
    -------------
    1 | 2 | 3
    Player1 (X) enter a number (1-9): 1
    .....

    .....

    X |   |
    -------------
    X | O |
    -------------
    X | O |

    Game over!

    The winner is player1!!!!

    Enter "Y" to play again: N

    Thank you for playing!
