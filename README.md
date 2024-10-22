# Pong_The_Famous_Arcade_Game 🏓

## Features
- **Ball:** Moves around and bounces off the walls and paddles.
- **Paddles:** Control two paddles (left and right) using the keyboard.
- **Scoreboard:** Keeps track of the left and right players' scores.
- **Collision Detection:** Detects collisions between the ball and the paddles, walls, and when the ball goes out of bounds.

### How the Game Works
1. **Ball Movement:** The ball moves continuously, bouncing off the top and bottom walls. If it hits a paddle, it changes direction.
2. **Paddle Control:** Each paddle can move up and down to prevent the ball from passing.
3. **Scoring:** If a player misses the ball, the opponent scores a point.

### Classes
- `Ball`: Manages the ball's movement, bouncing, and reset when out of bounds.
- `Paddle`: Handles the movement of each paddle.
- `Scoreboard`: Keeps track of the score and updates the display.

### Controls
- **Right Paddle:** Up arrow (↑) to move up, Down arrow (↓) to move down.
- **Left Paddle:** 'W' to move up, 'S' to move down.

### Example Gameplay

![Pong Game](https://github.com/user-attachments/assets/12b344e9-353a-40ef-bb3f-baa00a317e2c)

### How to Run
1. Clone this repository.
2. Run `python main.py` to start the game.

Enjoy the classic Pong experience!

