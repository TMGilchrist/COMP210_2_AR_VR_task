# COMP210_2_AR VR Task

# Pin-art Terrain Sculptor

## Design 

### Concept
The concept for this project is inspired by the Pinscreen toy (a metal grid of pins that can be pushed out to create images). The player will be able to sculpt a surface of pins into interesting shapes by raising and lower areas of the surface with hands, simulating a magnetism-like effect.

### Controller
Although a basic version of the project could simply use the Vive controllers in place of the user's hands, implementing hand tracking using the Leap Motion device would add an extra level of immersion by allowing the player to interact more naturally with the game. Handtracking would also allow for more nuance in the mechanics of the game, as the player could raise small areas with a pinch or large areas with a flattened palm.

For the prototype, I will simply be implementing the ability to raise the pins with an upturned hand, and lower them by facing the hand downwards.

### Core Mechanics:
* Surface grid of pins that can move individually.
* Ability to raise areas of the pins by aiming an upturned (palm up) hand at the pins.
* Ability to lower areas of the pins by aiming a downwards (palm down) hand at the pins.
* Ability to reset the surface.

### Further Mechanics

* Simulate a magnetism-like effect where raised pins pull neighbouring pins in the same direction.

### User Stories
* As a player I want to be able to see a grid of pins.
* As a player I want to be able to see a representation of my hands in the game.
* As a player I want to be able to be able to raise pins when my hands are facing upwards.
* As a player I want to be able to lower pins when my hands are facing downwards.



## Market Research

### VR Platform
The HTC Vive has over 35% revenue market share (as of Q1 2018) and is the lead VR platform in China. This shows there is a large audience of Vive users who would be able to play the game. In addition to this, it is supported by Unity, SteamVR and Leap Motion - all technologies I will be looking to use in this project.

### Game Potential
This mechanic could be integrated into a turn based strategy game as a terrain-altering mechanic. The player would be able to raise or lower a number of pins on the terrain grid, which could block or free unit movement across the board.

Alternativly, the raising of terrain could be the basis for a God Game or City Builder. The use of VR and Leapmotion control scheme could help immerse the player in the idea of being an omnipotent being shaping their world.



### Interesting Links:
http://hatchstudios.com/work/pin-art/

### Leap Motion:
https://forums.leapmotion.com/t/unofficial-vr-mount-thread/2296
https://www.leapmotion.com/technology/

### Reference Images:
https://www.menkind.co.uk/media/catalog/product/cache/49dcd5d85f0fa4d590e132d0368d8132/p/i/pin-art-hi-res-2.jpg
https://image.shutterstock.com/image-photo/pin-scape-260nw-331754117.jpg
http://hatchstudios.com/wp-content/uploads/pin_art_image01-1024x576.jpg

https://blog.vive.com/us/2018/07/26/think-vr-dying-just-getting-started/
https://d201n44z4ifond.cloudfront.net/wp-content/uploads/sites/6/2018/07/26074558/VR-Revenue-Share-730x410.jpg


