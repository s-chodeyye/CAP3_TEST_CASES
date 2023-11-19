# CAP3_TEST_CASES
Pong game

## Overview: Using the Pygame package, this Python script creates a simple version of the Pong game. A ball, a player paddle, and an AI-controlled opponent paddle make up the game. The goal is to bounce the ball back and forth between the paddles of the player and the opponent in order to maintain it in play.

## Usefulness:

### ball_animation(): - Adjusts the ball's position according to its present speed.
- Handles ball collisions with the game screen's left, right, top, and bottom limits.
- The ball_restart() function is triggered when the ball collides with the paddles of the player or an opponent.

### player_animation(): - Adjusts the player paddle's position in response to input from the player (up and down arrow keys).
Makes sure the paddle of the player remains inside the upper and lower bounds of the game screen.
## opponent_ai(): - Provides the opponent paddle with a basic AI.
. Depending on where the ball is, the opposing paddle rises or falls.
- Assures that the opponent's paddle stays inside the game screen's upper and lower borders.

### ball_restart(): - Places the ball back in the middle of the screen.
- Modifies the ball's starting direction and speed at random.

## Pygame Initialization: - This initializes Pygame and configures the width and height of the game window.
- Specifies the three paddles used in the game: the opponent, player, and ball.
- Determines the ball's starting direction and speed.
- Specifies the colors for the game's objects and background.
## Game Loop: - The script starts a never-ending game loop in which it watches for occurrences involving user input and modifies the game's elements in response.
. For a fluid gaming experience, the frame rate is managed by the clock object.

## Drawing: - Makes the screen clear before drawing the ball, the opponent's paddle, the player's paddle, and the center line.
Makes use of the drawing utilities in Pygame to draw ellipses and rectangles.

## Quit Event: - Handles the quit event to provide a smooth shutdown of the game window for the user.

## Controls: - The up and down arrow keys are used by the player to operate the paddle.

## Dependencies: - The Pygame library is necessary.
Use this code by copying and pasting it into a Python file.
. Ensure that Pygame is installed by running pip install pygame.
. Launch the Pong game by running the script.
