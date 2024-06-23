Tic Tac Toe Game in Java


## Overview
This is a Java implementation of the classic Tic Tac Toe game, using object-oriented programming concepts such as constructors, inheritance, abstraction, methods, classes, and objects.

## Game Description
The game is played between two players, Alice (human) and Robot (AI). The game board consists of a 3x3 grid, where players take turns marking a cell with either 'X' (Alice) or 'O' (Robot). The game checks for wins, draws, and invalid moves.

## Classes and Objects
The game consists of the following classes and objects:

1. TicTacToe: The main game class, which initializes the game board and provides methods for displaying the board, placing marks, and checking for wins and draws.
2. HumanPlayer: A subclass of Player, which represents a human player (Alice). It provides a method for making moves based on user input.
3. AIPlayer: A subclass of Player, which represents an AI player (Robot). It provides a method for making random moves.
4. Player: An abstract class that provides a common interface for both human and AI players. It includes methods for making moves and checking for valid moves.

## Features
3x3 game board
Human player (Alice) makes moves based on user input
AI player (Robot) makes random moves
Game checks for wins, draws, and invalid moves
Displays the game board and updates it after each move


## How to Play
Run the LanuchGame class to start the game.
Alice (human) makes the first move by entering the row and column numbers.
Robot (AI) makes its move randomly.
The game continues until either player wins or the game is a draw.
The game board is displayed after each move.

## Technical Details
Java version: 1.8 or higher
IDE: Any Java-compatible IDE (e.g., Eclipse, IntelliJ IDEA, NetBeans)
Compilation: Compile the TicTacToe.java and LanuchGame.java files using the javac command.
Execution: Run the LanuchGame class using the java command.

## License
This software is released under the MIT License. See the LICENSE file for details.

## Author
Yashraj M
