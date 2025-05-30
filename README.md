# Tic-Tac-Toe Game

A classic two-player Tic-Tac-Toe game implemented in Python for the console. Players take turns marking a 3x3 grid with **X** or **O**, aiming to get three of their symbols in a row — horizontally, vertically, or diagonally. The game ends when a player wins or when all cells are filled resulting in a draw.

---

## Features

- **Two-player mode**: Player X and Player O alternate turns.
- **Interactive console input**: Players enter the cell number (1-9) to place their mark.
- **Win detection**: Automatically detects if a player wins.
- **Draw detection**: Detects when the board is full and no player has won.
- **Input validation**: Handles invalid or already occupied cell inputs gracefully.

---

## How to Play

1. Run the Python script:

   ```bash
   python tic_tac_toe.py

The board positions are numbered 1 to 9 as follows:

1 | 2 | 3
---------
4 | 5 | 6
---------
**7 | 8 | 9**

Players enter the number corresponding to the cell they want to mark.

The game continues until a player wins or the game is a draw.

After the game ends, the winner is announced or a draw is declared.

**Code Overview**

1. print_board(board): Displays the current board state.

2. check_win(board, player): Checks if the current player has won.

3. is_draw(board): Checks if the game is a draw.

4. play_game(): Main game loop handling player turns, input, and game logic.

**Future Improvements**

1. Add Graphical User Interface (GUI) with Tkinter or Pygame.

2. Implement single-player mode with AI opponent.

3. Create a web-based version using HTML, CSS, and JavaScript.

4. Add score tracking across multiple games.

