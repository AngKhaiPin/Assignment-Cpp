# Part 2

## Video Demo

Please provide the YouTube link to your [Video Demo](https://youtube.com).

## Minimum Requirements

### Completed

List all the features completed.

1. Major bug fixes on alien movement
2. Implemented the alien trail, replaced the trails with game objects
3. Implemented zombie movement
4. Minor bug fixes on some UI : alien movement UI
5. Implemented multiple zombies movement
6. Implemented zombie distance calculation for zombie attack
7. Implemented alien attack zombie
8. Implemented zombie attack alien
9. Health pack works correctly according to alien hp
10. Arrow shown on HUD indicating which in game characters turn

### To Do

List all the features not yet done. Remove this section if there is no incomplete requirements.

1. if alien not in range of zombie, print out "zombie unable to attack alien"
2. after alien defeat zombie (if all zombie defeated, game ends)
a) after zombie remove from board
b) alien will continue that direction
c) no more movement for that zombie the next turn
d) HUD still shows the zombie wif 0 hp

3. after alien got defeated by zombie (game ends)
4. zombie choose new direction if hit alien or zombie
5. when alien hit pod, deal damage to zombie
6. Save & Load files


## Additional Features

Describe the additional features that has been implemented.

1. Alien health is change based on number of zombies.
2. 

## Contributions

List down the contribution of each group members.

For example:

### Ang Khai Pin

1. Fixed some of the game UI, during alien movement and when it ends
2. Implemented zombie movement and its UI
3. Improved on the rock items, so when alien hits the rock, will print out which object discover
4. Implemented multiple zombies movement
5. Implemented alien attack zombie

### Lester Liew Jun Min

1. Major bug fixes on alien movement
2. Implemented the alien trail and when alien turns ends, object will spawn
3. Minor bug fixes on zombie movement
4. Implemented zombie distance calculation for zombie attack
5. Implemented zombie attack alien
6. Implemented arrow shown on HUD to show which character's turn

## Problems Encountered & Solutions

Describe the problems encountered and provide the solutions / plan for the solutions.

1. Unable to retrieve the created vector data of zombie hp, attk, range. Solution: Use pass by reference
