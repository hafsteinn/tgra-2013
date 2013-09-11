#Computer Graphics Programming assignment 1: 2D computer game
This document describes the first programming assignment in the course
T-511-TGRA. The goal in this assignment is to write a fully functional, and
playable, 2D computer game.

#Project goal
In this project students can use LibGDX to make an OpenGL ES, or vanilla
OpenGL/Glut to implement their 2D game. Many students have been sending me email regarding programming languages. If you want to use some other exotic programming language - We don't care. Just be sure that you hand in your game with instructions how to build that game and list of requirements that we must install before running the game. If you pick paradigms that we are not used we might ask you to explain your code. 

The game must, at the very least,
include two objects, at least one of them moving by some rule and the
possibility of affecting some objects movement by input from the keyboard,
mouse, touchscreen or accelerometer. 

In most cases there will be more than one moving objects, some moving
automatically and some by input. In some cases the same objects will move by
some automatic rule and also be affected by input.

The game should include some form of collision detection between these objects
and other (static or mobile) objects that may be in the game. The game will
have some goal for the player and when that goal is fulfilled the program
should acknowledge the "victory" and start over (optionally at a more difficult
setting or in a new level). Certain situations shall also make the player
“lose” the game – the program will then acknowledge that fact and then start
completely over.
different colors. If these minimum requirements are fulfilled the game would
include two moving objects, each in it's own color. The following examples are
in now way the only options and students could possibly make some kind mix of
the two or take elements from a game that's not being implemented, just to
spice up their own game. It's a good idea to read the implementation ideas for
all these games even though a student may have made up their mind already.

#Android example 1 (also eligible for desktop): Gravity sling shot
Have the ball's direction change differently when it bounces off the racket, depending on where it hit the racket, in a way that the player can control the ball. Try to keep the ball's speed constant even though it's traveling slope changes.

If there is any childhood game that you miss and want to recreate we encourage you to implement that game. Be sure that your game fits the above mentioned requirements and please hand in description of the game logic. If you are not sure that your game fits the requirements you can send us email or describe your game logic in class.