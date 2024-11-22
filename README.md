# TurtleGame
This is a simple Turtle Crossing Game built using Python's built-in turtle module. The objective of the game is to control a turtle to cross a busy road filled with moving Squares, without getting hit. The turtle must reach the other side to score points, while avoiding collisions with the Squares.

## Features
- Player Controls: Use the up arrow to move the turtle upwards across the screen.
- Squares: squares move from the right to the left at different speeds.
- Game Over: The game ends if the turtle collides with a square.
- Score System: Players gain points each time they successfully cross to the other side.
- Multiple Levels: As the game progresses, Squares move faster and spawn more frequently.
  
## Game Controls
- Up Arrow: Move the turtle upwards across the screen.
  
## Scoring
Every time the turtle successfully crosses to the other side of the screen, the player scores a point.
The game continues until the turtle collides with a square, which triggers the game over screen.

## Screenshots
<img width="596" alt="Screen Shot 2024-11-22 at 1 20 25 pm" src="https://github.com/user-attachments/assets/0a1ac833-3bc9-4896-a0f4-3f87f35b3fa7">



## Code Overview
The game is implemented using the turtle module, which provides basic graphics and event handling. Key components include:
- Turtle Class: Defines the turtle's movement and position.
- Square Class: Defines the moving Squares, their speed, and position.
- Collision Detection: Checks for collisions between the turtle and the square.
- Score Display: Keeps track of the score and displays it on the screen.
- Game Loop: Manages the movement of the turtle and Squares, checks for collisions, and updates the screen.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
