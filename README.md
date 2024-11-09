# OO code using turtle graphics
- From the starting code, polygon_art.py, you are to write an OO program that generates different pieces of art works
- Fork, then, clone this repo
- Read the instructions given in the course's Google Classroom and start coding
- Once you are done, push your final code to your Github repo and modify this README to report on the work you have done

First, I forked the turtle_graphics_oo repository and cloned it to my computer.
In my code, I first imported turtle and random. I made a function that takes input because there are 9 possible results. Then, I set the speed, body color, tracer, and colormode for the turtle.

Next, I created a class called Turtle and made the __init__ function. The choice value comes from the input function.
I also made a gor function to calculate the number of sides for the shapes.
If the user chooses options 1, 2, or 3, I add 2 to the result, so the number of sides will be 3, 4, or 5.
If the user chooses options 4, 8, or 9, the result is random between 3 and 5 because these options can make a triangle, square, or pentagon.
For the other options, I subtract 2 from the result.

Then, I created a function to draw shapes like triangles, squares, and pentagons using a for loop. I used self.num_side to control the number of sides for each shape.

I also made a function to show a popup for options 5 to 9. After that, I made a function to draw the shapes with a for loop. I used an if-else statement to check if the choice is between 5 and 8 or if it is 9.
If the choice is between 5 and 8, the code runs with one function, but if the choice is 9, the code runs with another function because art 9 has a popup and also doesn't.

Finally, outside the class, I used another if-else condition. If the choice is between 1 and 8, it will loop 20 times and draw 20 shapes. But if the choice is 9, it will loop inside another loop because option 9 has a popup.

At the end, I called turtle.done() to finish the drawing.