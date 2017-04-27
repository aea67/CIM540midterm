# Documentation for CIM540 Final
[Game Link](http://agnesarchibong.com/hw/AirGuitarFinal/)


## Air Guitar Code Plan

Air Guitar is a game that teaches the user how to play notes on a guitar. 
It will play the notes first, then asks the user to play the notes with the animation.
The checking to see if the user got it right function has not been built out yet.

### Step One: Interface
I built on an interface from the wireframes I created in adobe Illustrator. They were hard coded lines, rectangles and ellipses on certain coordinate points that make it look like a guitar. 
 #### Inputs
* "play mode header" = rect
* "guitar frets" = stroke
* "guitar" = ellipse + rect
* "PLAY" button = createbutton
* tune1 = false

### Step Two: Hover Effect
Using the coordinate points from the interface, I added a mouse over function so that when the mouse was over a certain section it would change color. 
#### Inputs
* if (mouseX > x coord min && mouseX , x coord max && mouseY > ycoord min && mouseY < ycoord max){line stroke(color change) }

### Step Three: Strings Play
When play is pressed, it calls a function that changes tune1 from false to true.
When tune1 is true and the counter is less than or equal to 6, the strings play.
* if (counter <= 6 && tune1 == tune1 == true) { drawSong(counter)}
Using the coordinate points, I used a switch statement to animate the strings being played. 
#### Inputs
* switch(counter) 
once play was pressed the counter would begin, starting the strings
* counter++
only the sound plays at first. hitting play again triggers the animation
### Step Four: Guitar Sound
After play is pressed, a sound file starts playing. 
I recored myself playing guitar and then added it to an assets folder that the game links to. 
