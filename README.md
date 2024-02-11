

![image](https://github.com/mouncef121/pythondrawing/assets/152737532/7a57169d-9e1b-4dc7-b77b-e7e6f0af1dfc)

Explanation:

Imports: The turtle library is imported for drawing on the screen.
draw_spiral() function:
Sets the Turtle's speed to avoid visual flicker.
Sets the background color to black.
Defines a list of colors to be used in the spiral.
Loops 360 times, representing degrees:
Sets the current color based on the modulo operator.
Sets the line width based on the current iteration.
Moves the Turtle forward based on the current iteration.
Turns the Turtle left by 100 degrees.
draw_spiral() call: Executes the spiral-drawing function.
turtle.done(): Keeps the drawing window open until you close it.
