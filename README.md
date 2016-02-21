# Monster-Field

## Inspiration
The idea for this came from an old DS game. In this you had to take care of monsters and enter them into competitions. The end goal was to have some sort of fighting system like the original game but one person can only do so much.
I did this in Javascript mostly to push myself to try a new language. I have done some fiddling with JS before but nothing this massive.
## What it does
At the moment, you can move monsters between rooms and each room does something different. Each time the room's actions activate, the monster's stats change and a small notification appears on the monster. A health-bar will also change.

Each monster also wanders around and will collide with walls.

As a fun little test, I added the live status of the monsters. It is actively updated so every stat change is instantly shown.
## How I built it
With JavaScript and Phaser, a free open source JavaScript Game engine. Phaser handles the drawing of the sprites and physics.
## Challenges I ran into
Learning JavaScript and Phaser by myself. I was unable to split the tasks up and had to keep in mind a linear order for creation. Not that I could not skip around, but I was actively learning while writing so I worked on problems until fixed.

I also learned that not all physics engines are made equal. Part way though, I lost several hours b/c I discovered the default Physics Engine for Phaser is not able to handle collisions like I wanted and did not have sophisticated enough checking to accomplish my goals. The hours spent on redoing my entire system did make me learn though.
## Accomplishments that I'm proud of
Utilizing a physics engine. This is the first time I have even used a game engine, let alone a physics engine. So learning the strengths of each one and changing my entire program's skeleton to use it was a daunting task. But I survived and so did Monster Field.

I'm also proud that learned a great deal about JavaScript and its weakly typed variables. It was a shock to find that several times my number was taken as a string.
## What I learned
I learned a lot about JavaScript and its many different uses. Primarily that you can write HTML in JavaScript and set it in another container, essential making a very easy to use dynamic GUI.

Also having learned Phaser is not a bad thing. It had a wealth of resources and all my beginning questions could be answered with their numerous tutorials. 
## What's next for Monster Field
I want to add in eating and waste disposal in the room. That mostly entails adding some checks on the monsters to look for food and check if ready to eliminate waste.

I also want to add in a battle system. To keep it from being boring, a roulette of AI's would be created based off a monsters nature (brave, scared, silly, etc...). This would make each battle a little different and would not be too hard to add with JavaScript.
##How to use
Due to the use of Phaser and its requirement to be host on an http service, not locally, downloading the code will not work. The link provided should hold an active preview.
https://preview.c9users.io/tagger94/mob_field/index.html?_c9_id=livepreview0&_c9_host=https://ide.c9.io
