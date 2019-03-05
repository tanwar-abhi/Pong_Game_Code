# Pong_Game_Code

This repository contains code of a basic Pong-game which I worked on as a side projects of game development. 

This is the result of my personal interest and hobby in Game code development. 

Lua was used for the primary language.

main.lua => contains the main structure of the game which calls upon objects from the various classes 

Paddle.lua => It contains the object class defination for the rectangular paddles, including geometry and size of the paddles. This is called upon in main.lua.

Ball.lua => It contains object class definations for the ball, it includes ball geometry, speed and size definations.


push.lua => This is the push library that i downloaded from web which helps in rendering the game in a virtual width and height and gives a retro overlook to the entire game.

class.lua => This was an already existing library file that i downloaded from web, it helps in creating the object classes like Paddle and Ball so that the defination and calling of these can be similar to OOPS.

font.ttf => This is a custom font which is intended to give a retro vibe to pong game.

To run the game use the command "love ." from the folder that contains all the files and subfiles.