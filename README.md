# Othello Game with AI

This repository contains a Python implementation of the classic board game Othello (also known as Reversi) along with an AI player using the Minimax algorithm. The game can be played between a human and the AI.

## Features

- **Othello Game Logic**: Includes full implementation of Othello game rules.
- **AI Player**: An AI that uses the Minimax algorithm to decide the best moves.
- **Command-Line Interface**: The game can be played directly in the terminal.

## Files

- **`othelo.py`**: Contains the core game logic, including board initialization, move validation, and move execution.
- **`bot.py`**: Implements the AI player using the Minimax algorithm.
- **`main.py`**: Provides the command-line interface for playing the game.

## How to Run

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Shayannajafi03/Othello-with-minmax-alphabeta-.git
    cd othello-ai
    ```

2. **Run the Game**:
    ```bash
    python main.py
    ```

3. **Gameplay**:
   - The board is displayed in the terminal. 
   - Player 1 is human (`X`), and Player 2 is the AI (`O`).
   - Human players enter their moves in the format `row col`, where `row` and `col` are integers between 0 and 7.

---
