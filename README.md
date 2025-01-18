[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## W1L2 In-Class Activity
HW1 Break-Down Activity

Objects:
- UI
  - Seeds Planted UI
    - The count goes up one every time the player plants the plant
  - Seeds Remaining UI
    - The count goes down one every time the player plants the plant
- Player
  - Attribute
    - Bunny Sprite
  - Movement
    - Can go up, down, left, right and diagonally in each direction
- Plant Button
  - Press space
  - Has the ability to plant a single seed which then shows up on the screen.
  - Can only plant until the Seeds Remaining UI goes down to 0.
- Plants
  - Placed on scene at the location the player is when pressing the plant button
  - Once placed it effects the Seeds Planted & Seeds Remaining UI

## Devlog
From my breakdown activity, I had perfectly labeled the exact fields of code needed to be filled out. I labeled the PlantCountUI.cs as UI, Player.cs as Player, and my PlantSeed() function as Plants all in my breakdown. Though for my Plants section, I had neglected to put that my _numSeedsLeft and _numSeedsPlanted were to go down 1 and up 1, I had only addressed it as being "effected" which doesn't offer much to someone who had lost context of my breakdown.

When creating my plan for the project I hadn't added a list of values that would need to be instantiated in my Start function within my Player class. This is where I had go in and add my values that would update my seed counter as I had gotten stuck following strictly the notes from my breakdown which didn't include this needed part. Overall, I've learned that I need to be more precise in what my objects will being doing or affected by as it leaves less confusion when going back to complete the assignment.

## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites

## Prof comments
Thank you for connecting your break-down to the code that you wrote- you'll recieve full marks for this Devlog. :) In future Devlogs, I would like to see a little bit more detailed examples from your code- for example, you might talk about what functions you used that caused interactions between different objects in the game.

Please consider formatting your break-down activities with the hyphen '-' symbol as suggested above. Also, you can remove the prompt text. This will make it a lot easier for me to read. See the [README formatting guide here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
