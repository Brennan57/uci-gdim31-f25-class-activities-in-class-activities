# in-class-activities
## Devlogs
### W1
1. When the camera is moved off of the cat, it stops following the cat's movement. The cat is still able to move, yet the camera remains static. This is because the camrea is no longer attached to the "Cat" node, meaning the camrea will act indepentantly from whatever the "Cat" node does.

2. [My Week One Game](https://brennan-r.itch.io/roylo-b-catwalking)

### W2
1. r, g, and b are all floats because they are dealing with numbers with decimals

2. _bounce is an int because it is only counting the amount of times the ball bounces on an object. The amount of times it bounces will always be a whole number. Have you ever heard of a ball "half bouncing"?

3. It told me that I couldn't iterate on the variable because it was a float. Since I am itterating a float, I would need to put "f" at the end of the number, esspecilly if the number has a decimal.

### W3

We are Table #1

1. 
    1. The parameters to GetResponse would be an int for the friendship level and a bool for if the player knows the character's secret. The return type would be a string for the character's responce.

    2. The parameters for SetLightDimness would be an int for the player's sanity level. The return type would be a void, meaning that there is no return type.

    3. The parameters for DidPlayerHitBeat would be either a float or int (depends on how percise you want the check to be). The return type would be a bool, wether they hit it or not.

2. The metaphor that we thought of to compare componants and classes was to a human and the certain body parts they have. The classes are differnt body parts, and you attach them to a human (the componant) to allow them to fufill a desired task.

3. I think the balls get brighter becasue the code in step nine increaces the a multiplyer that increaces the RGB values. How fast the balls are moving increaces the multiplier since it is using the ball's x and y velocities. 

### W4
Table #1

1. We came up with the cat and soccer ball having the Rigidbody componant and the goal having the Is Trigger. The cat and ball are the two object that collide with each other, so they need to be able to have physics attached to them in order to move. The goal is still the entire time and the ball would want to phase through it as well. That is why the goal has the Is Trigger.

2. We got really confused when looking at the information for the Play() function. The document had a ton of information, but we were able to understand what the task wanted of us, and just simply called the function from _goalVFX. 

### W5

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 
