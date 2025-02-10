# Spiral-Circle
This project draws a spiral of circles using the Python `turtle` module.

## Developer

Neil Rathod

## Project Structure

The project consists of the following files:

- `main.py`: The main script that sets up the turtle environment and calls the function to draw the spiral of circles.
- `functions.py`: Contains the functions to draw a circle and a spiral of circles.

## Files

### `main.py`

This file contains the main function that initializes the turtle environment and calls the `draw_spiral_of_circles` function.

```python
import turtle as t
from functions import draw_spiral_of_circles

if __name__ == "__main__":
    t.penup()
    t.goto(0, -100)
    t.pendown()
    draw_spiral_of_circles()
    t.hideturtle()
    t.done()
