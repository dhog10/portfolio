[Back](https://dhog10.github.io/portfolio/)

## Unity

I have worked on many Unity projects, unity is currently the engine I am most experienced with. I have worked on projects for university coursework and many more personal projects in my spare time. My experience in Unity has greatly improved my understanding of 3D mathematics and manipulation of objects in a 3D space, ability to develop gameplay mechanics such as player controllers, weapons, interactable and dynamic items such as doors, elevators and much more.

### Uniscention
[Game Build (May perform poorly, optimization not a focus of four day game jam)](https://github.com/dhog10/portfolio/blob/master/builds/Uniscention.zip)

Uniscention is a game I worked on during the first game jam of my second year in University. This game was developed in four and a half days in a team of four designers and two programmers. I took on the task of creating mechanics such as the player movement, camera movement, character selection, interactable items and 3D menu buttons. The feedback received from my peers and tutors was very positive for this project, and I am very pleased with the final product.
![Uniscention Main Menu](images/uniscention_menu.jpg)
![Uniscention Character Selection](images/uniscention_menu2.png)
<video width="480" height="320" controls="controls">
  <source src="images/uniscention_player.mp4" type="video/mp4">
</video>

The player movement system in this game is very smooth, the player traverses adjacent to the face of the tower they are on, the player can also seamlessly move around faces by simply jumping around the cube or entering teleporters.

### Night in Notwellit
[Source](https://github.com/dhog10/LightGame)
[Game Build (May perform poorly, optimization not a focus of four day game jam)](https://github.com/dhog10/portfolio/blob/master/builds/NightInNotwellit.zip)

Night in Notwellit is the second game I worked on for my University group project module. Again, this game was developed in four and a half days with a team of four designers and two programmers. For this game I took on the task of creating the player controller, interactable items, holdable items, inventory system, UI & crafting mechanics, camera post processing config, procedural detail scattering, in engine setup of various prefabs, tooltips and objectives and enemy AI.
![Notwellit spawn](images/notwellit1.jpg)
![Notwellit Building](images/notwellit2.jpg)
<video width="480" height="320" controls="controls">
  <source src="images/notwellit_player.mp4" type="video/mp4">
</video>
My player controller for this game features intuitive and easy movement, with suitable and comfortable camera angles.
<video width="480" height="320" controls="controls">
  <source src="images/notwellit_enemies.mp4" type="video/mp4">
</video>
The enemies in Notwellit would not be able to enter light, which means the player would have to stay in the light to survive.

### Multiplayer Test
[Game Build (As of 22/01/2019)](https://github.com/dhog10/portfolio/blob/master/builds/MultiplayerTest.zip)

Multiplayer test is a personal project I have recently been working on to improve my understanding of network structure used in Unity, and my ability to setup game mechanics such as weapons and player controllers which function over a network. This project (As of 22/01/2019) was created over a period of roughly 3 days. I also improved my understanding of animations, blend trees and IK techniques during working on this project.
![Multiplayer UI](images/mptest1.png)
Custom multiplayer network UI
<video width="480" height="320" controls="controls">
  <source src="images/mptest_shooting.mp4" type="video/mp4">
</video>
Player controller & weapons written from scratch, supports first and third person, includes weapon hold animations, sounds and particle effects. Player traversal animations synchronized fairly well to footstep movements, movement appears in sync with footstep speed.
<video width="480" height="320" controls="controls">
  <source src="images/mptest_client.mp4" type="video/mp4">
</video>
Clients and weapons synchronized over a network, player animations and weapon effects calculated per client locally, accurate bullet trace synchronization.
<video width="480" height="320" controls="controls">
  <source src="images/mptest_pistol.mp4" type="video/mp4">
</video>
Supports first person aiming and also pistol hold types.

### Procedural terrain
This personal project was sparked by my interest in procedural generation techniques. I am very interested in procedural content such as terrain and item scattering. This project helped me develop my understanding of procedural techniques such as perlin noise and fractal algorithms such as diamond square.

### Space Multiplayer Game
I started this personal project to practise Unity multiplayer integration, and to practise creating a spaceship player controller. This was different to my previous experience in creating player controllers for regular traversing human characters, I also gained some experience in shaders written in CG by attempting a shader which would display a ripple effect when a projectile collided with a ships shield. This shader used a list of positions and times to calculate the intensity of the ripple effect at certain locations.

I unfortunately cannot currently provide the project source code, as some model files exceed 100MB (GitHub file size limit)
