Python version: >3.6
External Packages: numpy, matplotlib
Last update: 28th Nov 2021
Authors: Paulo Magalhães, Pedro Silva

Perceptron algorithm implemented by python using numpy, matplotlib.


It’s important to note that perceptrons are limited to solving problems that are linearly separable, ie., where it's possible to draw a single line to separate the classes. In this project we created a line and indicated that everything on one side of the line belongs to one class and everything on the other side belongs to the other class.

To initiate model we use random weights between 0 and 1. 
Then the user defines the number of iterations that algorithm will train in order to achieve the expexted result
For dataset we used a transistor example with 2 features.
[0,0]
[0,1]
[1,0]
[1,1]

Where if both features are 1 the result is 1 else if not.

At the end the model draws a plot with points and the line that separates both classes.