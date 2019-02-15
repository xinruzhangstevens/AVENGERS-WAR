GAME:PIRATE WARS
===
INTRODUCTION
===
This project aims to establish a game platform named "Pirate Wars" by module pygame in python. The game rule is that players move the pirate ship through the left and right keys on the keyboard. In addition, they destroy the enemy ships by launching bullets through the space bar until they finally meet the octopus monster. Once players defeat the monster by shooting bullets, it shows that they win the game. However, if the pirate ship collides with the enemy ship, it will show the end of the game.

FEATURE
===
Game Initialization
---
* set up window screen
* create time clock
* create sprites and sprite group

Game Loop
---
* set up refreshing frame rate
* events monitor
* collision checking
* Update/draw sprite group
* update screen display

TODO
===
Sprites and Sprite Group
---
* define sprites subclass 
* define derive sprite subclass

Construct Game Frame
---
* game initialization
* establish window screen by constant 
* build start game program
* realize alternating scrolling of background image
* simplify background implementation by initialization
* monitor exit events and exit games

Enemies
---
* define and monitor timers for creating enemy
* design and prepare enemy class
* timely creation and display of enemy 
* random position and random speed
* delete pictures of enemies out of the screen

Pirvate Ship
---
* prepare ship class
* draw private ship
* pirate ship cartoon effect realization (up and down)
* Control the left and right movement of the ship
* ship’s boundary control

Launch Bullets
---
* add and monitor events(bullets launched by pirate ships)
* define bullets class
* fire three bullets for one time

Collision Check
---
* collision between bullets and enemies
* collision between pirate ship and enemies 

Last Monster
---
* define monster’s class
* add and monitor the fire time of the monster
* add and monitor game winning time