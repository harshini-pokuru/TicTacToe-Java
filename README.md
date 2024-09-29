# Tic-Tac-Toe Game

This is a simple **Tic-Tac-Toe** game built using Java and Swing for the graphical user interface (GUI). The game allows two players to take turns placing their respective symbols (X and O) on a 3x3 grid. The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins. If all the grid cells are filled and no player has won, the game ends in a tie.

## Features

- **2-Player Mode**: Players X and O take alternate turns.
- **Winner Detection**: Automatically detects a winner when a row, column, or diagonal is filled with the same symbol.
- **Tie Condition**: Declares a tie when all grid cells are filled without a winner.
- **Graphical Interface**: Clean and simple GUI with interactive buttons for each grid cell.

## How to Play

1. Start the game by running the program. A 3x3 grid will be displayed.
2. The game starts with Player X, and the players take turns clicking on the buttons to place their mark.
3. After each turn, the game checks for a winner or a tie.
4. The game ends when either a player wins or all the tiles are filled.

## Code Overview

- **JFrame**: Used for the main window of the game.
- **JButton**: Represents each tile on the 3x3 grid.
- **JLabel**: Displays the game status (player's turn, winner, or tie).
- **GridLayout**: Used to arrange the 3x3 grid for the game board.

The game logic is implemented through event listeners that respond to button clicks, updating the board and checking for winning conditions.

## Winning Conditions

A player wins if:
- Three identical marks (X or O) are aligned either horizontally, vertically, or diagonally.

If the board is filled and no player has won, the game will declare a **Tie**.

## How to Run

1. Ensure you have Java installed on your machine.
2. Compile the `TicTacToe.java` file using the following command:
   ```bash
   javac TicTacToe.java
3. Run the game using:
   ```bash
   java TicTacToe

## Screenshot

![Screenshot (1157)](https://github.com/user-attachments/assets/3a77fc83-48ad-451e-b646-a8f289411d6d)

## License

This project is open-source and can be modified and distributed freely.

---

Enjoy the game!! 🎮
