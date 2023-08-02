# Biquadris
Biquadris is a variation of the game Tetris, expanded for two-player competition. 
A team of peers and I developed this video game for the final project of our CS246 (Object-Oriented Software Development) course. 

Coded in C++, the project follows object-oriented programming principles, employs the observer design pattern, and is structured using the Model-View-Controller (MVC) architecture. To ensure maintainability and scalability, the project is designed with low coupling and high cohesion. Each module is responsible for a single task and interacts with others through calls to public methods. 

## UML Diagram
Below is the UML diagram representing the structure of the Biquadris project, featuring over 27 classes, each designed with encapsulation in mind, using private fields to maintain data integrity. All superclasses are abstract to encourage polymorphism, enabling a flexible and extensible design.
<img src="/images/a4FinalUML.png" width="1000"> 

## Display
Our game supports both text-based and graphics-based displays using the XWindows library. The text display provides a simple and efficient way to interact with the game, while the graphics display enhances the visual appeal and creates a more immersive gaming experience.

<img src="/images/demo1.png" width="500">  <img src="/images/text.png" width="220">  
<img src="/images/nosfx.png" width="500">

## Gameplay
The primary objective of Biquadris remains similar to Tetris – to manipulate falling blocks and complete horizontal lines to clear the board. Players are free to choose between multiple difficulty levels (0-4) to adjust the game's challenge.

### Additional Special Features
* We added a **togglesfx** command to toggle graphics effects, allowing players to choose between faster rendering with lower graphics settings. 
* **blind**, **heavy**, **force** commands prompt players to make special choices when clearing multiple rows simultaneously. 
* Command names are auto-completed, and take an optional multiplier prefix to repeat actions multiple times. 



> ### Due to Policy 71, the source code is only available upon request.
