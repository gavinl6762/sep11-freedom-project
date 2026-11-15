# SEP 11 Freedom Project 
## Entry 1: Deciding and Tinkering with Tool
##### 11/9/26

#### Content
In my SEP11 class, students were required to choose a tool that will directly help support their freedom projetc idea. The tool that I decided on was ```Matter.js```, which is a 2D physics engine that is written in JavaScript. The tool includes multiple different simulatiosn that relates to physics; including gravity, collisions, friction, and bouncing. I chose ```Matter.js``` because I wanted to create a combat game that uses math functions as weapons. ```Matter.js``` would help in this project because of the collisions and gravity, etc. 

#### Engineering Design Process
The main goal was to build an interactive ball v ball combat game that uses math functions to attack. Since I had the idea already, I investigated the ```Matter.js``` documentation to understand how physics engines handle regid bodies like circles where you would use ```Bodies.circle```, bouncing which was ```resitution```, and collision which was ```collisionStart```. I thought about different ways to make the attacks work, like having each hit do the exact same damage or making faster hits do more damage. At first I tinkered with bouncing. Setting it closer to 1 made them bounce heavily, while 0 will make it the object bounce it lower. The code I tinkered in jsbin was: ```const ball = Bodies.circle(100, 100, 30, {restitution: 0.9 });```, this gave the ball a bounce level of 0.9 which wasn't too high. The next property that I learned was ```engine.world.gravity``` because the game I wanted to create couldn't have any gravity so that it would continuously bounce. For example, I did the code ```engine.world.gravity.y = 0;``` which turned the gravity off completely so that the ball will glide around.

#### Skills/Professionalism
Some skills that I practiced and gained was using objects and different shapes that I tinkered with using collisions and bouncing, by using jsbin I was able to see reactions of the code where I was able to see the objects crash using ```collisionStart```. Also, by reading and testing the vectors, speed ```Vector.magnitude```, gravity ```engine.world.gravity```, and bounciness ```restitution```, it helped me understand more on how objects interacts.

#### Sources 
```brm.io/matter-js``` - main homepage 
```brm.io/matter-js/docs``` - the official guide that covers all properties

[Next](entry02.md)

[Home](../README.md)