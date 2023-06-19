# Processing Sketch

This is a Processing sketch that demonstrates a simple animation with two bouncing balls.

## Prerequisites

To run this sketch, you need to have Processing installed on your computer. You can download Processing from the official website: [https://processing.org](https://processing.org)

## How to Run

1. Open the sketch in Processing.
2. Click the "Play" button or press Ctrl+R (Cmd+R on Mac) to run the sketch.
3. You should see a window with two bouncing balls.

## Description

The sketch creates two instances of the `Ball` class, each representing a ball with a specific color. The balls move around the screen, bouncing off the edges. When the balls collide, they change direction.

The `Ball` class has properties for position (`x` and `y`) and color. It also provides methods for randomly generating the initial position and drawing the ball on the screen.

The animation is achieved by updating the position of the balls in the `draw()` function using predefined speed values. The balls change direction when they reach the edges of the screen or collide with each other.

## Customize

You can customize the sketch by modifying the following variables in the `MySketch` class:

- `speedX`: The horizontal speed of the first ball.
- `speedY`: The vertical speed of the first ball.
- `speddX2`: The horizontal speed of the second ball.
- `speddY2`: The vertical speed of the second ball.
- `Ball` constructor calls: You can change the color values passed to the `Ball` constructor to modify the colors of the balls.

Feel free to experiment and modify the sketch to create your own animations!


