- Game is relative simple,
	- Two camera angles provided, use 'c' to toggle between them
	    1. Overview
	    2. Shoulderview
	- Player movement using, 		 
	    1. w -> forward, s -> backward, a -> turn left and d -> turn right, when using an overview camera.
	    2. mouse could be used to look around when using the shoulder view camera. 
	- tap "space" key to fire a bullet towards the direction player is facing.
	- Used NavMesh for the enemies to move and fire towards the player at all time.
	- Only way to avoid a bullet is to dodge the bullet or make is collide into a wall, since bullet moves faster then the player you cannot outrun.
	- player's bullet moves faster than the enemy's bullet.
	- player move faster than the enemy.
- Key rules:
	1. Player cannot touch wall or cannot collide with enemy or cannot get shot by enemy, this ends the game instantly.
	2. Enemy gets destroyed if they collide into wall or with each other or get shot by a bullet.
	3. Enter into the empty space in the maze to win the game.
	4. Game resumes every 3secs after the player dies.
	5. To quit press alt+f4.
- I have made use of an online free asset called "Detonator Explosion Framework" by Ben Throop for my explosion effects.

- https://docs.unity3d.com/Manual/index.html was a really helpful documentation in understanding Unity libraries better.
- To run the game simply click on MyFirstGame in the package.

Extra Credits:
- Here is a link to the game preview video and I have tried explaining about the game here.   
	https://drive.google.com/file/d/1ANmTh6TFrNn2qE2KpZw3O8VHhtihpc3D/view?usp=sharing 
  I give full access to the Source code and all the other assets developed by me to the instructor and TA's of CSC561 - Computer graphics course at NCSU.
- Would like to claim extra credits for implementing shoulder view on player.
