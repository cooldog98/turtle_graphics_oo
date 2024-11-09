# OO code using turtle graphics
- From the starting code, polygon_art.py, you are to write an OO program that generates different pieces of art works
- Fork, then, clone this repo
- Read the instructions given in the course's Google Classroom and start coding
- Once you are done, push your final code to your Github repo and modify this README to report on the work you have done

First I fork turtle_graphics_oo, then I clone it to my computer.
In the part of coding first import turtle, ramdom, make the function input because it can be 9 type of result and set 
the value of speed, body color, tracer and colormode . After, make class Turtle, make def __init__(self, choice) choice 
come from function input. Then make def gor calculate the num of side. Therefore, I make if user choose 1, 2 and 3 the 
result will + 2 so the num of side will be 3, 4, 5 respectively, and if user choose 4, 8 and 9 the result will random 
between 3 amd 5 because art 4, art 8, art 9 can be triangle, square and pentagon. Residue the result will -2. After, 
I make def that run turtle be triangle, square and pentagon by use for loop and call self.num_side to make each shape. 
Then, make def for make the popup for art 5 to art 9 after that make def for draw by use for loop, and if-else by 
condition if choice stay between 5 and 8 code will run with def choice_n if choice is 9 code run with def choice_n. 
Then, out of class use if-else agine with condition if choice between 1 and 8 it will loop 20 loop or draw 20 time but,
if choice is 9 will be loop in loop because art 9 have popup and not popup. In the end call turtle.done() 
to final turtle.

