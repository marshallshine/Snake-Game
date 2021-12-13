# Java Snake Game
This is a simple snake clone written in Java following [this tutorial](https://www.youtube.com/watch?v=bI6e6qjJ8JQ). I've added a couple of additional features to the existing tutorial. For example, on line 121 in the GamePanel.java class I've added a for loop that checks to make sure apples do not spawn on the snake body. I've also added restart functionality. In the same class on line 211 I added a case to my switch statement that allows the user to press enter if the game is not running to open a new JFrame. 

There are a couple of bugs that I am still trying to fix. For example, my restart function opens a new window, but leaves the old one open too. I'm trying to get it to either a) restart the game on the same windows, or b) close the JFrame when a new one is opened. Another bug I am trying to fix is that if the user presses down and left at the same time while the snake is moving horizontally the snake will die and the game will end. Same thing if the user presses up and right at the same time while the snake is moving vertically.

The actual code is in the master branch because I don't know how to use Git and it scares me.


