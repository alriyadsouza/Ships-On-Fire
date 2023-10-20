# Battleship Game

Welcome to the Battleship game project! This is a classic two-player strategy game where you'll be arranging your ships and attempting to sink your opponent's fleet. We invite you to contribute to this open-source Python project to enhance the gameplay and bring new features to the table.

## Rules of the Game

Before you start contributing, it's important to understand the rules of Battleship:

- The game is played on two square grids, one for each player, typically 8x8 in size.
- Each player secretly arranges their ships on their grid. There are three ship types:
  - Battleship (3 squares)
  - Submarine (2 squares)
  - Patrol Boat (1 square)
- The number of ships of each type is the same for both players.
- Ships must be placed without overlapping and occupy consecutive squares either horizontally or vertically.
- The game begins with players taking turns guessing the coordinates to target their opponent's ships.
- A successful hit results in the announcement of the sinking of that ship.

## Project Structure

The Battleship project is structured as follows:

- **`battleship.py`**: The main Python script that runs the game.
- **`board.py`**: A module responsible for creating and managing game boards.
- **`player.py`**: A module that defines the player class.
- **`ship.py`**: A module that defines the ship class.
- **`utils.py`**: A collection of utility functions used throughout the project.

## Contribution Guidelines

We welcome your contributions to improve the game. Here's how you can get involved:

1. **Fork the Repository**: Click the "Fork" button in the top right of this repository to create your copy.

2. **Clone Your Fork**: Use `git clone` to clone your fork to your local machine.

3. **Create a New Branch**: Make a new branch for your contribution. This helps keep your changes isolated from the main code.

   ```bash
   git checkout -b feature/your-feature-name
