# Engines-Assignment-1

This is the level editor assignment for Game Engine Design and Implementation. The levels in my group's GDW game is not set in stone and therefore, we don't know yet how exactly they will look. For this assignment, I decided to create a basic level that could resemble the obstacles player interact with in the GDW game. The player-controlled object can jump, move and uses the environment objects to make it to the end of the level, the door.

The objects used in this assignment were all either made by me or already in the unity registry. The platforms, character, door, floor and sky were all made using cubes, spheres and planes. The staircase was made by me in blender and transferred into Unity.

The brick material used for the platforms was made by me in Adobe Substance Designer. The player's material was made in Photoshop by me. The ground and sky materials were basic materials in Unity. The door material was received from online at https://dekewood.en.made-in-china.com/product/lwSJopzPHrcu/China-Contemporary-White-Primed-Moulded-HDF-Doors-with-Texture-Surface.html

Even though it was removed from the requirements, press Z to enable/disable gravity, press C to enable/disable collisions (which will cause the player to fall through the ground as there will no longer be collision to keep it up) and press V to enable/disable lighting.

The other third-party things I used for this assignment involves the move player code. In a tutorial for Social and Multiplayer Game Design, we created the ability to move a player using rigidbody and AddForce. I referenced this code, with adjustments to allow for jumping, better collisions, etc. to move my character.
Additionally, we created a WebGL build in this tutorial and I used that method to make a WebGL build for this assignment.
