# Documentation for CIM540 Final

## Air Guitar Code Plan

Air Guitar is a game that teaches the user how to play notes on a guitar. 
It will play the notes first, then asks the user to play the notes with the animation.
The checking to see if the user got it right function has not been built out yet.

Step One: Interface
I built on an interface from the wireframes I created in adobe. They were hard coded lines, rectangales and ellipses on certain coordinate points that make it look like a guitar. 
Inputs

I will have a start button that the user must click on to start the game.

Outputs

Once the button is pressed, the output is the strings playing, which look like different line sections of the guitar lighting up

Pseudocode

Play button when tune1 = 1 and counter = 0, clicking PLAY: starts game and counter++

Lines start highlighting in sequence, and stop when finished. tune1 becomes false and counter = 0

hitting play makes game play sequence again.
