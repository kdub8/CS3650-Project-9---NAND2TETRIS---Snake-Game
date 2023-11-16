# CS3650-Project-9---NAND2TETRIS---Snake-Game

This project presents a classic Snake Game implemented in Jack. The game includes various classes to manage the game state, handle user input, track scores, and represent the game grid.

## Classes

The game consists of the following classes:

- **Main**: The main class initiating the Snake Game.
- **RandSeed**: Generates a seed value based on user input.
- **Random**: Provides methods for generating random numbers within specified ranges.
- **Snake**: Represents the snake in the game environment.
- **SnakeGame**: Manages the entire Snake game including the game loop, user inputs, and game state.
- **SnakeGrid**: Represents the grid where the SnakeGame is played.

## Game Description

The game operates as follows:

- **Initialization**: Upon initiation, the game sets up the Snake, grid, and initializes variables.
- **Game Loop**: The game loop runs continuously, handling user input for movement, collision detection, and managing game state changes.
- **Scoring and Levels**: As the Snake consumes food pellets, it progresses through levels, updating scores and possibly increasing difficulty.
- **Game Over**: The game ends when the Snake crashes into itself or the player chooses to exit.

## Instructions

To run the Snake Game:

1. **Setup**: Ensure you have the appropriate Jack environment configured.
2. **Compilation**: Compile all Jack files using the Jack compiler.
3. **Execution**: Run the compiled Snake game file.

## Usage

The Snake Game provides a classic arcade-like experience. Use arrow keys for directional movement, 'P' to pause, and 'Q' to exit the game.
