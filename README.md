# ⭕ TIC TAC TOE ✖️ - (Terminal Edition) 

# Rules of Tic-Tac-Toe
Following are the rules that define how to play the tic tac toe game:
```
  - A player can put only a single letter X or O in the 3 x 3 grid in each chance.
  - Both players will get chances alternatively one after another till someone wins or draws. 
  - To win this game, the player must create a horizontal, vertical, or diagonal line consisting of three same letters.
  - The game is drawn, if all grids are filled with X or O letters but no line is made.
```
# Feature of Tic-Tac-Toe in C++
This game provides the following features:

- This game is developed on a `3x3` grid.
- This game is designed for `2 players`.
- Every player may choose a letter between `X` and `O`.
- Both players will get their chances to turn by turn.
- 
# Components of the Game
The game is made of the following components that include the functions and data structures to provide the basic operations of the game.

## 1. Game Board
The game board is managed by the Board class which contains:

- A 3x3 character grid to represent the board.
- A counter to track filled cells.


## 2. Movement Of Player
The Boardclass includes methods to handle player moves:

- drawBoard() to display the current state of the board
- isValidMove() to check if a move is valid
- makeMove() to update the board with a player's move

> [!TIP]
> How to check if the input is valid or not?
>
> - Valid input: If the cell is empty and is within the boundary (0-2 for internal tracking, 1-3 for user input)
>
> - Invalid input: If the cell has already been filled with another letter or is outside the bounds

## 3. Win, Lose or Draw
The Board class includes methods to check game status:

- checkWin() to determine if a player has won
- isFull() to check if the board is full (a draw)
- The draw condition is checked in the play() method of the TicTacToe class when the board is full and no player has won.

# Result
![image](https://github.com/user-attachments/assets/ee767888-2379-411f-82a4-aa48eeb31447)
