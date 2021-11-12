# Week7-Menus
 NYU Week 7 Menus 


Buttons 
-- Created script for button functions
-- Found bug: Quit button on ThirdPerson scene loaded FirstPerson scene then there was not a Pause game function on FirstPerson scene. Cause of bug was incorrect spelling in code
and no option to load a specific scene. I copied code from MainMenu script and replaced loadScene code in PauseMenu script. This fixed bug. I then created a prefab of the PauseMenu Canvas
and EventSystem object. Imported into FirstPerson and Isometric scenes.