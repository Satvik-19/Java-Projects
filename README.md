This is a Java program that is based on the Tic Tac Toe game, the code working is explained in short and easy way below:

1. The `TicTacToe` class is the main class that contains the `main` method.
2. Inside the `main` method, a 2D character array `board` is created to represent the game board, and it is initialized with spaces.
3. The game starts with the player 'X' and a loop is executed until the game is over.
4. In each iteration of the loop, the current state of the board is displayed using the `printBoard` method.
5. The player is prompted to enter the row and column indices to make a move.
6. If the chosen cell is empty, the player's move is recorded on the board, and the `haveWon` method is called to check if the player has won the game.
7. If the player has won, a message is displayed, and the game ends.
8. If the game is not over, the player is switched from 'X' to 'O' or vice versa.
9. If the chosen cell is not empty, an error message is displayed, and the player is asked to try again.
10. The `haveWon` method checks for three possible winning conditions: rows, columns, and diagonals.
11. The `printBoard` method is a helper method that prints the current state of the game board.

Note: This implementation doesn't handle the case of a tie game, and it assumes that the user will enter valid row and column indices.
      I am working on improving the project. 
