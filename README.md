# UE4 - Zelda Breath of the Wild Sheikah Runes
<p align="center">
  <img src="./DemoRessources/SheikahOrbs2.gif" width="550" height="200">
  <br><b>Recreation of the 4 Sheikah Runes mechanics from Zelda Breath of the Wild using the Unreal Engine 4 (V4.25.3).</b>
</p>


## Introduction

This project features :
* Four distinct Sheikah Runes (Remote Bombs, Cryonis, Stasis, Magnesis) working gameplay mechanics.
* Complete User Interfaces working like the full game for each rune.
* Basic melee combo system for interacting with stasis objects.
* A demo level in the form of an Shrine, where you can test the abilities in four rooms and collect orbs.

## Basic Interactions
<p align="center">
  <img src="./DemoRessources/CarryDropBomb.gif">
  <br><i>Link can carry and drop objects</i>
</p>

Those interactions are common for severals objects. 
For now Link can :
* Carry objects
* Drop objects
* Launch objects

The animation blueprint uses IK on both hands based on two sockets found in the object carried.

  
## Sheikah Runes preview 💣❄️🔒🧲


### Remote Bombs 💣

### Cryonis ❄️
<p align="center">
  <img src="./DemoRessources/CryonisCreate.gif">
  <br><i>Link can create ice pillar on water surfaces</i>
</p>

With the <b>Cryonis</b> rune, Link can create and destroy pillars on water surfaces. The system handles pillars created horinzontaly (from a cascade).

### Stasis 🔒
<p align="center">
  <img src="./DemoRessources/StasisHit.gif">
  <br><i>Link can hit froze objects to create momentum</i>
</p>
 
With the <b>Stasis</b> rune, Link can freeze objects in time, allowing him to create momentum by hitting them. 
  

### Magnesis 🧲
<p align="center">
  <img src="./DemoRessources/MagnesisCarry.gif">
  <br><i>Link can carry any magnetic object</i>
</p>
  
 With the <b>Magnetic</b> rune, Link can carry big magnetic objects. He can pull or push the objects.
 
## User Interface

The project include a working and faithful user interface, with several widgets, all animated.

I designed the UI to be all event-driven by severals event dispatchers in order to isolate each system. 

## Demo Shrine

<p align="center">
  <img src="./DemoRessources/ShrineCryonis.png" width="640" height="360">
  <br><i>Preview of the room for the <b>Cryonis</b> rune<i>
</p>

For testing purposes, a little Demo Shrine is included in the projet. The player must face challenges to collect one orb for each rune, showing that the mecanics are working correctly.

## Work in Progress
* Add sound effects to the demo (I need to find some ressources online with the sounds from the game).

## Disclaimer
The user interface uses the Nintendo Switch controller scheme. 

## Credits
* Animation System - [Advanced Locomotion System V4](https://www.unrealengine.com/marketplace/en-US/product/advanced-locomotion-system-v1)
* Hammer and Snowflake Icon by [Freepik](https://www.flaticon.com/authors/freepik)
* Sword animations from [mixamo](https://www.mixamo.com)
* Particle Pack by [Kenney](https://www.kenney.nl/assets/particle-pack)
* Arrow model from [Mix and Jam](https://www.youtube.com/channel/UCLyVUwlB_Hahir_VsKkGPIA)
* Ice material by [Dean Ashford](https://www.youtube.com/watch?v=sE64iTjnoUM)
* Rounded cube from [Acceloroto](http://acceleroto.com/2013/08/game-prototyping-rounded-cube-3d-model/)
* Additional UI elements from [Paul "Superfondue" Rey](https://www.instagram.com/superfondue/)
* Grid materials from [SuperGrid](https://www.unrealengine.com/marketplace/en-US/product/supergrid-starter-pack)
* All assets from Zelda Breath of the Wild are used for educational purposes only
