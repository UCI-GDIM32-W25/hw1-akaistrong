[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## W1L2 In-Class Activity

Put your notes from the W1L2 (Thurs, Jan 9) in-class activity here.
HW1 Break-Down Activity

Objects:
UI
Seeds Planted UI
The count goes up one every time the player plants the plant
Seeds Remaining UI
The count goes down one every time the player plants the plant
Player
Attribute
Bunny Sprite
Movement
Can go up, down, left, right and diagonally in each direction
Plant Button
Press space
Has the ability to plant a single seed which then shows up on the screen.
Can only plant until the Seeds Remaining UI goes down to 0.
Plants
Placed on scene at the location the player is when pressing the plant button
Once placed it effects the Seeds Planted & Seeds Remaining UI

## Devlog
Prompt: Include the HW1 break-down exercise you wrote during the Week 1 - Lecture 2 (Jan 9) in-class activity (above). If you did not attend and perform this activity, review the lecture slides and write your own plan for how you believe HW1 should be built. If your initially proposed plan turned out significantly different than the activity answers given by Prof Reid, you may want to note what was different. Then, write about how the plan you wrote in the break-down connects to the code you wrote. Cite specific class names and method names in the code and GameObjects in your Unity Scene.


Write your Devlog here!

From my breakdown activity, I had perfectly labeled the exact fields of code needed to be filled out. I labeled the PlantCountUI.cs as UI, Player.cs as Player, and my PlantSeed() function as Plants all in my breakdown. Though for my Plants section, I had neglected to put that my _numSeedsLeft and _numSeedsPlanted were to go down 1 and up 1, I had only addressed it as being "effected" which doesn't offer much to someone who had lost context of my breakdown.

When creating my plan for the project I hadn't added a list of values that would need to be instantiated in my Start function within my Player class. This is where I had go in and add my values that would update my seed counter as I had gotten stuck following strictly the notes from my breakdown which didn't include this needed part. Overall, I've learned that I need to be more precise in what my objects will being doing or affected by as it leaves less confusion when going back to complete the assignment.


## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites
