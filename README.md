# Tic-Tac-Toe-game 
Purpose--: The code snippet represents a simple implementation of a tic-tac-toe game (also known as “noughts and crosses”).

Functionality--:

The game allows two players (X and O) to take turns by clicking on the game board.
The game tracks the number of moves (up to 9) to determine if it ends in a draw.
It checks for a winning pattern (3 in a row) and displays the winner (either X or O).
There are buttons to reset the game and start a new one.

Key Components:

boxes: Represents the individual cells on the game board.
turnO: A boolean flag to alternate between X and O players.
count: Keeps track of the total moves made.
winPatterns: Defines the winning combinations (rows, columns, diagonals).

Functions:

resetGame(): Resets the game state.
gameDraw(): Handles a draw scenario.
disableBoxes(): Disables all cells.
enableBoxes(): Enables all cells.
showWinner(winner): Displays the winner.
checkWinner(): Checks for a winning pattern.

Event listeners:

Click events on each cell trigger the game logic.
Buttons for resetting the game and starting a new one.
Overall, the code provides a basic tic-tac-toe game with win detection, draw handling, and user interaction. 😊
