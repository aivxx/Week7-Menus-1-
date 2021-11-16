# Week7-Menus
 NYU Week 7 Menus 


Buttons 
-- Created script for button functions
-- Found bug: Quit button on ThirdPerson scene loaded FirstPerson scene then there was not a Pause game function on FirstPerson scene. Cause of bug was incorrect spelling in code
and no option to load a specific scene. I copied code from MainMenu script and replaced loadScene code in PauseMenu script. This fixed bug. I then created a prefab of the PauseMenu Canvas
and EventSystem object. Imported into FirstPerson and Isometric scenes.

Chest Animator
-- Created parameters in animator for chest open/close
-- Created Chest Behavior script for trigger of treasure chest

Animations
-- Created copy of chest open animator, recreated chest opening on X axis at 150 degrees over 60 frames/1sec.
-- Added to ChestBehavior script to log when chest has opened - good code for adding sound upon a trigger
-- Created firefly animations. Each firefly has a animation on it's pointlight to pulsate at different times and intensities. 