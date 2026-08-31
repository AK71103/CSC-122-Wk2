# A Class-ic Hero's Journey lab

Create a class representing a Hero.

A hero has (variables for):
-A strength value, that is assigned randomly when they are created. Code outside the class should be able to read this value, but not write to it.
-A courage value, that is assigned randomly when they are created. Code outside the class should be able to read or write this value.
-A name, that is set by the constructor. Code outside the class should be able to read this value, but not write to it.

A hero can (has functions to):

-Attend training for some length of time (the argument), which increases their strength proportionally to the time.
-Attend therapy, which increases their courage by a random amount.
These functions should be accessible outside the class.

There should be an external (not in the class) function which sends a hero on a quest:

-The quest should end in success, failure, or a neutral result. A better outcome should be more likely for heroes with higher strength.
-The quest should reduce the hero's courage, with them losing more for worse outcomes.
-The quest should print the hero's name and the result to the terminal.

You should test this code by creating several heroes, and performing their various functions repeatedly.

Tips:

-Make sure your random results return different values each time you run the program!
-Recall that classes typically have getters and setters
-Review how a constructor function works
-The specification leaves the details of implementation up to you. Consider the requirements, and make decisions for what data types you need for the variables and functions to be able to fulfill their requirements.



Your code should be submitted as a GitHub link!

When you're done, answer the following Thought-Provoking Questions:

1) What data types did you use for the hero's internal variables? Could other types have functioned as well?

2) How easy would it be for you to expand your code, giving your hero new stats and things they can do?

3) This is a framework that could be used as part of a game. Is there anything that feels like it's missing? Any obvious expansions you would make to this code?

