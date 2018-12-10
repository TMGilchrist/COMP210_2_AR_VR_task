# COMP210_2_AR VR Task

# Pin-art Terrain Sculptor

## Design 

### Concept
The concept for this project is inspired by the Pinscreen toy (a metal grid of pins that can be pushed out to create images). The player will be able to sculpt a surface of pins into interesting shapes by raising and lowering areas of the surface with hands.

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
Although my prototype focuses mostly on creating a mechanic, I have also considered possible 

### VR Platform
The HTC Vive has over 35% revenue market share (as of Q1 2018) and is the lead VR platform in China. This shows there is a large audience of Vive users who would be able to play the game. In addition to this, it is supported by Unity, SteamVR and Leap Motion - all technologies I will be looking to use in this project.

### Game Potential
Although my prototype focuses mostly on creating a mechanic, this could then be integrated into a number of different games. One of the most likely potential games would be a turn based strategy game with a terrain-altering mechanic. The player would be able to raise or lower a number of pins on the terrain grid, which could block or free unit movement across the board. Alternativly, the raising of terrain could be the basis for a God Game or City Builder. The use of VR and hte Leapmotion control scheme could help immerse the player in the idea of being an omnipotent entity shaping a world.

### Current Games
Skyworld: This is an example of a turn-based strategy game designed for VR. Players overlook a floating world based on a hex-grid and interact with units and buildings to defeat their opponent. With Very Positive reivews on Steam and 4/5 stars on oculus.com, this shows that turn-based strategy is viable in VR, and something that users enjoy. However, Skyworld is a reletively expensive game, selling for £23.79 on Steam, £21.57 on the Vive store and £18.99 on the Oculus store. A much cheaper title - focusing on using creative strategies using the ability to change the board's terrain - could be a viable product.

From Dust: From dust is a God simulator where the player can control matter such as water and earth to interact with tribes of people living on islands. The game is $14.99 (£11.87) on the Ubisoft store and £8.59 on Steam. It was also Ubisoft's fastest selling digital game at the time, with over 70,000 copies sold in the first week. https://www.gamasutra.com/view/news/126374/Ubisoft_From_Dust_Marks_Companys_Fastest_Selling_Digital_Release.php

While the game allows the player to act as a god to the villagers in the game, using a mouse and keyboard to interact with the game on a screen does not enhance the feeling of being a god. The ability to see the world in VR and to change that world with your hands would add depth and immersion to the experience. A simple simulation game where you can alter and affect people or animals in a world by raising and lowering terrain to change water levels or block passes could be appealing to users who enjoyed From Dust.

## Resources
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


