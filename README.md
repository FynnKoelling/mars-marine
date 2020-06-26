# mars-marine

Unreal Engine 4 Project - Showcase Visual Scripting (Blueprint) with focus on object-oriented programming

following the course "Unreal Engine Blueprint Developer: Learn Visual Scripting" on GameDev.tv 
https://www.gamedev.tv/p/unreal-blueprint last visited 09.06.2020 16:09

Materials and Static Meshes are course assets

### Controls
#### Keyboard and Mouse
* Control the Pawn with W,A,S,D
* Aim with Mouse
* Fire with Left Mouse Button
* Press Escape Ingame to Pause Game
#### Gamepad
* Control the Pawn with Left Thumbstick
* Aim with Right Thumbstick
* Fire with Right Trigger

Mars_Marine_Project: Project Files (.uproject)

Editor Startup Map: "Mars"
	
Blueprints containing amongst other things:
* Custom Pawn BP_Marine
	* Damage System for and through AI
	* Line Tracing Weapon System
	* Controls for Keyboard / Mouse and Gamepad
* AI BP_Alien
	* Damge System for and through Pawn
	* Follow and Attack System
* Wave System implemented in "BP_MarsMarine_GameMode"
* Animation Blueprints under Characters - [Character] - Animations
	* Blended Poses
	* State Machines
* UI
	* Menu System
	* HUD

WindowsNoEditor: Application (.exe) for Win64 (Controls see above)

	

