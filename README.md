![Capture](https://github.com/CultyMarble/NotJetpackJoyride/assets/13515227/2b2e00c5-adfe-41ac-bb5a-6a41b29d6463)
# **PROJECT OVERVIEW**
This is a game project I contributed for ***VGP135-Intro To Mobile Programming*** course at ***Lassale College***.
The project is the best attemp at clone a very famous arcade mobile game: Jetback JoyRide. We had been working on it for 11 weeks.
In this project I work as a technical artist, my main job is to create pixel art for the game and implement systems that require fine-tuning between art and programming like the background generator.

![Animation](https://github.com/CultyMarble/NotJetpackJoyride/assets/13515227/75ee0aee-2c0d-4627-a8ec-4b9f5b271709)
## **CONTRIBUTED FREATURES:**

### 1. COIN SYSTEM
#### Key features:
- Read input pixelated images and instantiate coins object base on the image.
- Read input pixelated alphabet images and print out coin according to input text.
- Pool system: all coins are instatiated initially and properly reuse.
- Weigth system: the coin generation system can randomize weigth so it can pick between spawning text or spawning patterns
#### What are the challenges?
- I have to learn how to use image system within unity to write and read image. And learn how to use it optimally since reading image can be very expensive.
#### What can be improved?
- The coin system can only handle pixelated images; therefore, it heavily depends on the artist to create and fine-tune every patterns, It is suggested to add feature that help the system read from images of any resolution, then resize and create a suitable patterns to fit into pre-defined the game screen.

![heart](https://github.com/CultyMarble/NotJetpackJoyride/assets/13515227/090cb747-810f-4ce7-b243-98099b1bd637)
![AnimationCoin](https://github.com/CultyMarble/NotJetpackJoyride/assets/13515227/c87c3a62-65f0-4caf-8eb1-25c40a7d2ad2)
### 2. BACKGROUND GENERATOR
#### Key features:
- Create an seamless moving background for the game.
- Background consist of background cells, which can be customize freely for randomness.
- Generator can spawn cell of any width and heigth without breaking the distance.
#### What are the challenges?
- Because of the time constrain, there is a lot of trial and error in the process to make this system modular. There are still band-aid solution need to be addressed in the system to optimize the system.
#### What can be improved?
- Unlike coin generator, background cell is created by actively instatiate and destroy, wich is very wasteful. The content displayed in each cell still have to be manually placed and adjust. There would be difficulty to add differnt theme of background into to the mix.

![AnimationBG](https://github.com/CultyMarble/NotJetpackJoyride/assets/13515227/c5805108-2b71-402a-9c12-0cd4cb7b8dec)

### 3. ART
#### Key features:
- Player sprites + animation
- Obstacle sprites
- Background sprites
- Basic lighting system
- UI/UX

![player_sheet_default](https://github.com/CultyMarble/NotJetpackJoyride/assets/13515227/338acbbe-4c23-4102-9ead-7e7031b879ea)
![basic_bg_tile_v02](https://github.com/CultyMarble/NotJetpackJoyride/assets/13515227/d2d522d8-1ceb-445a-bef1-5d58ae22a9ba)
