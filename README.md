# 3DUnityGraphicsApplication
This is a demonstration of various light constructions in Unity Engine
## Week 6
### First Commit Changes for this week
Changes:
- Created an enclosure in the SampleScene
- Changed the Color of the TransitionLight game object
- Created a new script (LightGenerationScript.cs) that created more TransitionLight objects and deletion of said objects
- Added Folder Structure of the files from the last commit

Problems:
- Would delete all instances of the object immediately
- Attaching a light object to a demo model for navigation/exploration purposes
### Second Commit Changes for this week
Changes:
- Implemented First Person Camera
- Attached a flashlight in sync with the camera
- Implemented a dummy model courtesy of Kevin Iglesias

Problems:
- Camera controls attached to the model is not synced and therefore disable at the moment
- Creating a LightSource increases light intensity each time.
## Week 7
### First Person Movement
Changes:
- Incorporated movement with the body model, camera, and light source
- The camera has sensitivity that is able to be adjusted
- Movement speed is able to be adjusted

Problems:
- None spotted
### Light Shadows

Changes:
- The light sources in the model are now using hard shadows
- The mouse cursor is now hidden and locked in place when the game is running
- Adjusted syntax part of the attempt to deal with the exponential problem of instantiated light sources

Problems:
- None spotted
