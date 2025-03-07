# Cameron Fox

Hi! I'm Cameron, I'm a games developer and 2nd year computer science student at the Univeristy of Cambridge. My games, many game-jam entries and my Steam release Anchor Up, are released under "Orange Flag Studio". I am also the co-founder and co-president of the Cambridge University Game Development Society (CU-Devs), alongside Samuel Shakeshaft. I intend to update this page with games and programming projects that I do in between my studies.

## Links 

### Personal
- [Itch.io page](https://orange-flag.itch.io/)   - 19 online game jam entries
- [Github](https://github.com/badwolf2828)     
- [YouTube channel](https://www.youtube.com/@orangeflagstudio7841)
- [LinkedIn](https://www.linkedin.com/in/cameron-fox-970216273/?trk=opento_sprofile_topcard)

### Cambridge University Game Devlopment Society

- [Instagram](https://www.instagram.com/cudevs/)
- [Society Page](https://www.cambridgesu.co.uk/organisation/cu-devs/)
- [Cambridge Game Jam 2025](https://camgamejam.com/#about)    - Ran in partnership with CUCATs
- [CU-Devs vs Gamma, University of Hokkaido Game Jam](https://itch.io/jam/gamma-vs-cudevs)    - Possibly the first international univeristy vs university game jam

- [Article about the founding of the society](https://www.cai.cam.ac.uk/news/more-game-caians-set-game-dev-society)

## Current Projects

### 3rd Person Cover System - Unreal Engine C++ [Continuing]

Standing bits of cover with transitions to/from crouch added. 

Planning to add: cover transitions and vaulting (and possible extension of the same system for climbing?). Would also be nice to make it into a bit more of a game! Obvious choice has to be some stealth game... Currently using a construction worker character so just need to come up with some post-apocalyptic context!
[Short Video](https://www.linkedin.com/feed/update/urn:li:activity:7282817796915298304/) 
[Devlog of work so far](https://youtu.be/_-vrriGN1yU) 

### First Person Puzzle Platformer - UEFN + Verse Group Project

The group project I am working on at university is a global state setting puzzle game being made in Unreal Engine for Fortnite (therefore using Verse). I have overhauled the UI and wrote a custom inventory system so we can have our own items in the game, something not currently extensible within the default Fortnite inventory and UI.


(Updated 07/03/2025)

## Projects and Experience  

### Anchor Up
[![Anchor Up Trailer](https://img.youtube.com/vi/aNCixTz0mXI/0.jpg)](https://www.youtube.com/watch?v=aNCixTz0mXI)  
[Anchor Up - Steam Page](https://store.steampowered.com/app/1384000/Anchor_Up/)  
Turn-based strategy puzzle game I independently made (art, code, etc...) in 15 months between April 2020 and August 2021, made in Unity (using C#). Implemented the Steam Cloud required file structure system in the saving of player progress, and the use of Steam Achievements. Responded to feedback received in the [Jonas Plays Your Game](https://www.youtube.com/watch?v=Tjy0-ewKuYk&t=1s) video in which the game was playtestsed, specifically updating the graphics for player movement and adding a realtime tutorial.

### 3rd Person Cover System
[![Cover System Devlog](https://img.youtube.com/vi/_-vrriGN1yU/0.jpg)](https://youtu.be/_-vrriGN1yU)  
Using Unreal Engine 5 and C++, I implemented multi-segment cover rails as well as full wrap-around cover (e.g. moving around a box) with appropriate character rotation per segment. I controlled the cover animations using a blend-space within animation Blueprints, all other logic was wrote in C++. I wrote a custom component to make the creation process for new pieces of cover streamlined, new pieces could be created and dragged into the editor and would work straight away as demonstrated [here](https://www.linkedin.com/feed/update/urn:li:activity:7282817796915298304/).

### DNGN
[![DNGN Trailer](https://img.youtube.com/vi/x7JMQEBYFqI/0.jpg)](https://www.youtube.com/watch?v=x7JMQEBYFqI)  
[DNGN - Fair Build](https://cu-devs.itch.io/dngn-freshers-fair-ver)  
4 player gamepad dungeon crawler. Co-lead alongside Sam Shakeshaft. I designed the Enemy AI system such that enemies could use the same weapons as players and this would affect their behaviour. I also implemented the entire audio system, including the audio that was used, and the major gamelooping features (ensuring the resetting of game state and singletons on death). Learnt to handle Git merges on a larger scale than I had before.

### C++ Particle System  
[![Particle System Video](https://img.youtube.com/vi/LH8dyr6qCl8/0.jpg)](https://www.youtube.com/watch?v=LH8dyr6qCl8)  
I completed the Sumo Digital C++ course using their one-line game engine. I then used the framework to create my own particle system, demonstrated in the video above. This was then reviewed by a developer at Sumo Digital who was able to provide valuable feedback about code efficiency improvements.

### 3rd Person Ledge-Climbing Character Controller
[![3rd Person Controller Video](https://img.youtube.com/vi/JsnFtw4QK7k/0.jpg)](https://www.youtube.com/watch?v=JsnFtw4QK7k)  
Solo project where I created the logic for a 3rd person character controller and camera for a stealth game demo in Unity. The USP for the stealth game was the ability for the character to dash through walls, and also dash through enemies to kill them. The ledge climbing also implemented corner transitions and slope climbing.

### Photography Weather App  
[![3rd Person Controller Video](https://img.youtube.com/vi/3fuzVbWm56s/0.jpg)](https://www.youtube.com/watch?v=3fuzVbWm56s)  
Team project for the Interaction Design course. I implemented custom element animations, filtering-by-condition (e.g. if you wanted to take a rainy photo, it would show you the nearest locations where it is currently raining) and a tab system such that the weather-data pages could easily be swapped between by clicking the add button and then clicking on tabs at the bottom. Used React-Native. Taught me how to code web apps using hooks and events.

### GeoTIFF to 3D Model - Flat Route Planner
[![Route Planner Video](https://img.youtube.com/vi/OsSs4PIqN9k/0.jpg)](https://www.youtube.com/watch?v=OsSs4PIqN9k)  
Created a GeoTIFF to 3D model generator. I then adapted the A* pathfinding algorithm to find the flattest routes, with a variable max-incline that the pathfinder will then try to adhere to. Taught me how to decode TIFF formatted data and the representation of 3D models at a lower level - something I have learnt much more about at university since.  

### Procedurally Generated Boss Fights
[![Procedural Boss Fights Video](https://img.youtube.com/vi/PD7mZSkJmu4/0.jpg)](https://www.youtube.com/watch?v=PD7mZSkJmu4)  
Used a delegate function strategy for procedurally generating bosses. Movesets are generated at the start of the fight, each boss starts with a certain number of "points" which it then spends on moves or behaviours to add to its moveset, it also spends them on burst moves (e.g. dash three times in a row) and combinational moves (e.g. throw a bomb and jump). Upcoming moves affect the enemy's behaviour, such that if a ranged move is planned to happen next then the boss will try and create distance from the player.
