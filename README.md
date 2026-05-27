# Python Snake Game

The classic snake game made in [Python Tkinter](https://docs.python.org/3/library/tkinter.html). Written for Python3 by [GeeksforGeeks](https://www.geeksforgeeks.org/snake-game-in-python-using-pygame-module/). Licensed under the [MIT License](https://choosealicense.com/licenses/mit/).

<div align="center">
<img src="graphic.jpg" alt="Snake Game image">

Simple Snake Game
</div>

## Basic Instructions

Use the arrow keys to move: the left arrow key to move left, the right arrow key to move right, the up arrow key to move up, and the down arrow key to move down.

## How to play

- Clone the repository:

```
$ git clone https://github.com/autruonggiang/Simple-Snake-Game.git
```

- Install Python:

Make sure Python is installed on your system. You can download it from the official [Python website](https://www.python.org/).

- Open the project in Visual Studio Code:

Open Visual Studio Code and click on "File" -> "Open Folder...".
Select the folder where you cloned your repository.

- Run ```game.py```:

With the Python file open, press ```F5``` or ```Ctrl + F5```. This will execute ```game.py``` in the integrated terminal.

- Play the game:

Once the game is running, follow the instructions to play the Snake Game. Typically, you'll use arrow keys to control the snake.

## About the Game
<div align='center'>
<h4> <span> · </span> <a href="https://www.youtube.com/watch?v=SUtHKHwUKT4"> Documentation </a> <span> · </span> <a href="https://github.com/autruonggiang/Simple-Snake-Game/issues"> Report Bug </a> <span> · </span> <a href="https://github.com/autruonggiang/Simple-Snake-Game/issues"> Request Feature </a> </h4>
</div>


# "Fork created during a Civic Education class from the modified initial code of autruonggiang — Class III C, Computer Science, ITIS Galilei, Livorno, Italy"

#Changes:
#FOOD color from #FFFF00 to #E04124
#SNAKE color from #0000FF to #E01919
#name at line 144 
#added an extra / at lines 39 and 41 to workaround for a syntax change related to the previous version of Python
#WIDTH from 500 to 600
#HEIGHT from 500 to 600
#SPEED from 200 to 180
#BACKGROUNF from #000000 to #FFFFFF
#ADDED: Dynamic frenzy mode (speed increases if no fruit is eaten within 5 seconds).
#ADDED: Progressive multiple fruits system (1 extra fruit every 4 blocks of snake length, max of 4 fruits simultaneously).
#ADDED: Poison fruits that spawn after obtaining 20 points, eating one doesn't kill you but the second does. They last each 4.5 seconds and then disappear.