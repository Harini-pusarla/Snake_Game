# Snake_Game
This project is a classic Snake Game developed using Python’s tkinter library for GUI rendering. The player controls a snake that moves around a rectangular grid, eats food to grow longer, and must avoid running into the walls or itself to survive.

## Key Features:
Grid-based game field using a Canvas widget.

Snake growth logic: Eating food increases the snake's length and the player's score.

Collision detection: Game ends when the snake hits the wall or itself.

Real-time control using arrow key bindings (← ↑ → ↓).

Score tracking displayed at the top.

Game Over message centered on the screen upon losing.

## Technologies Used:
Python 3

Tkinter (for GUI components)

Random module (for food placement)

## Game Logic Summary:
1.The snake is initialized with a default length.

2.The game loop (next_turn) moves the snake in the current direction at regular intervals.

3.On each move:

If food is eaten, the snake grows and score increases.

If not, the snake moves forward by removing the last segment.

The game checks for wall or self collisions.

4.Arrow key presses update the snake's direction with rules to avoid reversing instantly.

5.The game ends with a GAME OVER screen if a collision is detected.
