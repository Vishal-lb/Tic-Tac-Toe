# Tic-Tac-Toe

##This is a simple command-line Tic Tac Toe game implemented in C. 
##The game allows two players to play against each other on a 3x3 grid.

#Features
-->Two-player gameplay.
-->Simple and clear command-line interface.
-->Automatic checking for wins and draws.

#Requirements
-->C compiler (gcc, clang, etc.)
-->Terminal to run the game.

#Installation
-->Clone the repository (or download the source file):


##git clone https://github.com/Vishal-lb/Tic-Tac-Toe
  ->cd tic-tac-toe

Compile the program:

gcc -o tic_tac_toe tic_tac_toe.c

Usage

#Run the compiled program from your terminal:


#How to Play
-->The game starts with Player 1.
-->Players take turns to enter a number between 1 and 9 to place their mark (X for Player 1 and O for Player 2) on the board.
-->The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins.
-->If all 9 cells are filled and no player has 3 marks in a row, the game is declared a draw.

#Game Controls
-->Enter a number: Players are prompted to enter a number corresponding to an empty cell on the board where they wish to place their mark.
-->The board is displayed after each move, and the game checks for a win or draw condition.

#Example

=== TIC TAC TOE ===

     |     |     
  1  |  2  |  3  
_____|_____|_____
     |     |     
  4  |  5  |  6  
_____|_____|_____
     |     |     
  7  |  8  |  9  
     |     |     

Please enter number for Player 1: 5

=== TIC TAC TOE ===

     |     |     
  1  |  2  |  3  
_____|_____|_____
     |     |     
  4  |  X  |  6  
_____|_____|_____
     |     |     
  7  |  8  |  9  
     |     |     

#Code Overview

->initializeBoard(): Initializes the board with numbers 1 to 9.
->printBoard(): Clears the screen and prints the current state of the board.
->playerMove(int player): Prompts the current player to enter their move and updates the board.
->checkWin(): Checks if there's a winning combination on the board.
->checkDraw(): Checks if the board is full and the game is a draw.
->switchPlayer(int *player): Switches the turn to the other player.

#Contributing
##Contributions are welcome! Please fork the repository and submit a pull request for any bug fixes or enhancements.

#Contact
For any questions or suggestions, please contact [vishallbsinghrajput@gmail.com].
