# Snake Game in Assembly

This project is an implementation of the classic Snake game, tailored for the Gecko4Education EPFL-Edition board. It has been written in assembly language, making it a great resource for those interested in low-level programming and hardware interaction.

## Features

- **Directional Control**: Use the board's buttons to navigate the snake.
- **Scoring System**: Eat food to increase your score, displayed on the board's 7-segment display.
- **Game Over Detection**: The game ends when the snake collides with itself or the boundaries.
- **Checkpoint System**: Save and restore game states at certain score intervals.

## Prerequisites

To run this game, you will need:
- Gecko4Education EPFL-Edition board
- Assembly language toolchain compatible with the board
- Basic understanding of assembly language and hardware programming

## Installation

Clone the repository to your local machine using:

```bash
git clone https://github.com/<your-username>/<repository-name>.git
```

Navigate to the cloned repository:

```bash
cd <repository-name>
```

## Controls

- **Left Button**: Move the snake left
- **Right Button**: Move the snake right
- **Up Button**: Move the snake up
- **Down Button**: Move the snake down
- **Checkpoint Button**: Save the current game state (available at certain score intervals)
