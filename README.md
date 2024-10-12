# Pong Game

This is a classic Pong game implementation using Python's Turtle graphics library. The game features two paddles controlled by players, a ball that bounces between them, and a score tracking system.

## Features

- Two-player gameplay
- Paddle movement controlled by keyboard inputs
- Automatic ball movement with increasing speed
- Score tracking for both players
- Ball bounces off paddles and walls
- Game reset when a player scores

## Files

- `main.py`: The main game loop and setup
- `paddle.py`: Contains the Paddle class, managing paddle behavior
- `ball.py`: Manages the ball object and its movement
- `Score.py`: Handles score display and tracking

## How to Run

1. Ensure you have Python installed on your system.
2. Install the required libraries (only built-in libraries are used, so no additional installation should be necessary).
3. Run the game by executing the `main.py` file:

   ```
   python main.py
   ```

4. Use the following keys to control the paddles:
   - Right Paddle: Up Arrow (move up), Down Arrow (move down)
   - Left Paddle: 'W' key (move up), 'S' key (move down)

5. Try to hit the ball with your paddle and make your opponent miss to score points.
6. The game continues indefinitely, keeping track of each player's score.

## Game Controls

- **Right Paddle**:
  - Up Arrow: Move paddle up
  - Down Arrow: Move paddle down
- **Left Paddle**:
  - 'W' key: Move paddle up
  - 'S' key: Move paddle down

## Game Mechanics

- The ball starts moving in a random direction at the beginning of each round.
- The ball's speed increases slightly each time it hits a paddle.
- When the ball passes a paddle, the opposing player scores a point, and the ball resets to the center.
- The game continues until manually closed.

## Customization

You can customize various aspects of the game by modifying the constants in the respective files:

- Adjust paddle size or speed in `paddle.py`
- Change ball speed or size in `ball.py`
- Modify the screen size or game boundary in `main.py`
- Alter the scoreboard appearance in `Score.py`

## Contributing

Feel free to fork this project and make your own modifications. Some ideas for enhancements:
- Add a start menu
- Implement an AI opponent for single-player mode
- Add sound effects
- Create power-ups or obstacles
- Implement a win condition (e.g., first to 10 points)

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
