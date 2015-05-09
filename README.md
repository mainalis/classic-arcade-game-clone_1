frontend-nanodegree-arcade-game
===============================

This arcade game consist of main folder called project 3. under this directory 
user can find following file and folders.
1. index.html
2. js (folder)
3. images (folder)
4. css (folder)

i) loading game

(a) To start a arcade game user has to open index.html file. 
index.html use app.js, engine.js and resources.js (three javascript files).
app.js file consist of instance of enemy and players objects, implementation of
collision between player and enemies. implementation of movement functionality for player and 
enemies object.
resource.js file consist of implementation logic of loading the rescources (images) used in this aracde game.
engine.js file  implements the rendering of objects used in this arcade game.

(b) Images folder consist of images used in this arcade game.

(c) css folder consists of style.css and responsible for styling index.html

*******************************************************************************************************

ii) Playing game

a) when user load the game in his browser, arcade game will visibible on middle 
of browser where player is reside on bottom centere and enemies on top.

b) the main goal of player is to cross the pathway and reach the other side
	with out colliding with the enemey(i.e bug).
c) to achieve this goal user has to use the up, down, left and rigth arrow from the keyboard

d) when user cross the pathway and reach other side he finished his objecive
