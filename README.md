# Tic-Tac-Toe Game
This is a simple implementation of the classic Tic-Tac-Toe game using Java. It allows two players to play against each other on a command-line interface.

## Features
Player vs Player mode: Two human players can take turns to play the game.
Interactive command-line interface: The game provides an intuitive interface for players to make their moves.
Win detection: The game automatically detects when a player wins or if the game ends in a draw.
Error handling: Invalid moves and incorrect inputs are handled gracefully, with appropriate error messages displayed to the players.
## Installation
To run this game on your local machine, make sure you have the following prerequisites:

Java Development Kit (JDK) 8 or higher installed on your machine
Command-line interface or terminal
Follow these steps to get the game up and running:

Clone this repository to your local machine using the following command:

`git clone https://github.com/your-username/tictactoe-java.git`

Navigate to the project directory:

`cd tictactoe-java`

Compile the Java source code:

`javac TicTacToe.java`

Run the game:

`java TicTacToe`

## How to Play
When you run the game, the empty Tic-Tac-Toe board will be displayed on the command-line interface.

The game will prompt Player 1 to make the first move. Players take turns to make their moves.

Each move is made by entering the coordinates of the desired position on the board. The coordinates should be entered in the format row column (e.g., 1 2, 3 1, etc.), where the row and column numbers range from 1 to 3.

The game will validate the move and update the board accordingly. If a player makes an invalid move (e.g., selecting an occupied position or entering incorrect input), an error message will be displayed, and they will be prompted to make another move.

The game will continue until a player wins or the game ends in a draw. The result will be displayed on the command-line interface, and the players will be given the option to play again or quit the game.

## License
This project is licensed under the MIT License. Feel free to modify and distribute it as per your needs.

## Acknowledgments
The project structure and implementation were inspired by various Tic-Tac-Toe examples available online.
Thanks to the Java community for providing helpful resources and tutorials.
