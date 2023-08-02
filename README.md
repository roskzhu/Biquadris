# Biquadris
Biquadris is a variation of the classic game Tetris, expanded for a two-player competition. 
A team of peers and I created this video game for the final project of the CS246 (Object-Oriented Software Development) course. 

We coded this in C++ and incorporated objected-oriented programming principles, the observer design pattern, and the Model-View-Controller (MVC) architecture. The project is also designed with low coupling and high cohesion to ensure maintainability and scalability.

## UML Diagram
Below is the UML diagram representing the structure of the Biquadris project:
<img src="/images/a4FinalUML.png" width="1000"> 

Our final project has over 27 classes, each designed with encapsulation in mind, keeping its fields private and promoting data integrity. All superclasses are abstract to encourage polymorphism and enable flexible design and extensibility.

## Display
Biquadris supports both text-based and graphics-based displays using the XWindows library. The text display provides a simple and efficient way to interact with the game, while the graphics display enhances the visual appeal and offers a more immersive gaming experience.
| <img src="/images/demo1.png" width="400">| <img src="/images/demo1.png" width="400">|
|:--:| :--:| 
| _graphics display with sfx on_ |_graphics display with sfx on_|
<figure> <img src="/images/demo1.png" width="400">  <figcaption></figcaption> </figure> <figure> <img src="/images/nosfx.png" width="400">  <figcaption>graphics display with sfx off</figcaption> </figure> <figure> <img src="/images/text.png" width="200">  <figcaption>text display</figcaption> </figure>

## Gameplay
The primary objective of Biquadris remains similar to Tetris - to manipulate falling blocks (tetrominoes) and create complete horizontal lines to clear the board. Players are free to choose between multiple levels(0-4) to increase/decrease difficulty.

### Special Features
* We added a **togglesfx** command to turn on/off a better graphics display, so graphics can be chosen to render faster with lower graphics settings.
* **blind**, **heavy**, **force**: prompts player to choose a special command when 2 or more rows are cleared at a time.
* command names are auto-filled to completion, and can take a multiplier prefix to be repeated multiple times. 
<figure> <img src="/images/blind.png" width="500">  <figcaption>player 2 with blind effect on</figcaption> </figure> 

### Source Code
Due to Policy 71, the source code is only available upon request.
