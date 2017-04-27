# Documentation for CIM540 Final
[link] (http://agnesarchibong.com/hw/AirGuitarFinal/)

## Air Guitar Code Plan

Air Guitar is a game that teaches the user how to play notes on a guitar. 
It will play the notes first, then asks the user to play the notes with the animation.
The checking to see if the user got it right function has not been built out yet.

### Step One: Interface
I built on an interface from the wireframes I created in adobe. They were hard coded lines, rectangales and ellipses on certain coordinate points that make it look like a guitar. 
 #### Inputs
* "play mode header" = rect
* "guitar frets" = stroke
* "guitar" = ellipse + rect

### Step Two: Hover Effect
Using the coordinate points from the interface, I added a mouse over function so that when the mouse was over a certain section it would change color. 
#### Inputs
* if mouseX && mouseY (stroke(color change))

### Step Three: Strings Play
Using the coordinate points, I used a switch statement to animate the strings being played. 
* switch(counter) 
once play was pressed the counter would begin, starting the strings
* counter++
only the sound plays at first. hitting play again triggers the animation


Outputs

Once the button is pressed, the output is the strings playing, which look like different line sections of the guitar lighting up

Pseudocode

Play button when tune1 = 1 and counter = 0, clicking PLAY: starts game and counter++

Lines start highlighting in sequence, and stop when finished. tune1 becomes false and counter = 0

hitting play makes game play sequence again.
