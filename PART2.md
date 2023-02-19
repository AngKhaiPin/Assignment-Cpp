# **Part 2**

## <u>**Video Demo**</u>

Youtube Link      : [Video Demo](https://youtu.be/dISNkdj1vAA). <br/>
Our Personal Github Link :  [GitHub Link](https://github.com/V3ness/PF2223-Assignment)<br/>
#### **Please refer to our Personal GitHub Link to access the commits, as we usually push our commits to Personal instead of this Repository.**


<br/>
<img src="https://www.linkpicture.com/q/maxresdefault_6.png" type="image" alt="Bugs can go be damned" width="400">
<br/><br/>

## <u>**Minimum Requirements**</u>

### <u>Completed</u>

List all the features completed.

1. Major bug fixes on Alien movement.
2. Implemented the Alien trail, replaced the trails with game objects.
3. Implemented Zombie movement.
4. Minor bug fixes on some UI : Alien movement UI.
5. Implemented multiple Zombie movements..
6. Implemented Zombie-Alien Distance calculation for various functions such as Zombie Attack and pod Object.
7. Implemented Alien attacking Zombie.
8. Implemented Zombie attacking Alien.
9. Print out Zombie unable to attack Alien when Alien is not in range.
10. Alien attack reset after its turn.
11. Health pack works correctly according to alien hp.
12. Arrow shown on HUD indicating which in game characters turn.
13. Added arrow command, user needs to put in correct position and direction.
14. Added quit command.
15. Improved on pod object to damage the nearest Zombie.
16. Implemented the part where alien got defeated by Zombie.
17. When Alien gets defeated by Zombie, will ask user if they want to restart the game.
18. Added gameover function.
19. Added save and load command.
20. Implemented functions to save and load game files.
21. Improved on pod object to check if Zombie is defeated or not.
22. Implemented the part where Zombie got defeated by Alien.
23. When Zombie gets defeated by alien, that Zombie will be removed from the board and alien will continue in that direction, but sometimes it will stop, completely randomised. 

## <u>**Additional Features**</u>

Describe the additional features that has been implemented.

1. Alien health is changed based on number of Zombies.
2. Added Encryption System to make sure the user cannot change the file without prior knowledge.
3. Added "Safety Net" to various places where it requires input from user such as Rows and Columns to avoid situation like having 0 rows or columns ***<u>(try it out)</u>***
4. A difficulty setting in which preset rows, columns and no. of zombies are set depending on which difficulty the user chose.
5. The amount of blank spaces will adjust based on amount of grids on the board to make it fair.

## <u>**Contributions**</u>

List down the contribution of each group members.

### <u>Ang Khai Pin</u>

1. Fixed some of the game UI, during Alien movement and when it ends.
2. Implemented Zombie movement and its UI.
3. Added additional feature 1.
4. Improved on the rock items, so when Alien hits the rock, will print out which object discover.
5. Improved on the health items, so that Alien hp is recover accordingly.
6. Implemented multiple Zombies movement.
7. Added arrow command.
8. Added quit command.
9. Referred to Lester's pass by reference method to implement Alien attack Zombie.
10. Improved on the Zombie attack Alien where Zombie is unable to attack alien when not in range.
11. Added gameover function to implement the part where Alien got defeated by Zombie.

### <u>Lester Liew Jun Min</u>

1. Major bug fixes on Alien movement.
2. Implemented the Alien trail and when Alien turns ends, random objects will spawn.
3. Minor bug fixes on Zombie movement.
4. Implemented Zombie distance calculation for Zombie attack.
5. Implemented pass by reference method for Zombie attack Alien / Alien attack Zombie.
6. Implemented Zombie attack Alien.
7. Implemented arrow shown on HUD to show which character's turn.
8. Improved on the pod object to deal damage to nearby Zombie
9. Improved on when Alien got defeated by Zombie, reset the values for a new game.
10. Added save and load command.
11. Implemented functions to save and load game files.
12. Improved on pod object to check if Zombie is defeated or not.
13. Implemented the part where all zombies gets defeated by alien.
14. Added additional features from 2 to 5.

## <u>**Problems Encountered & Solutions**</u>

Describe the problems encountered and provide the solutions / plan for the solutions.

1. Unable to retrieve the created vector data for Zombie hp, atk, range / alien hp. <br/>
><b>Solution:</b> Use pass by reference method.
2. The vectors were glitching out when doing save/load function call.
><b>Solution:</b> Found out it was due to vector size not being transferred properly when saving and loading, and fixed it.
3. The Zombies were constantly crashing into one another and consuming each other
><b>Solution:</b> Added a bool value for if the Zombies are crashing into one another, and made a function to make sure overlapping doesn't happen.
4. Alien and Zombies were going out of bounds and causing ***Segfaults*** (kill me)
><b>Solution:</b> Added bool for hitBarrier to stop Alien/Zombie from moving any further.
5. Zombie numbers were going haywire after it moves.
><b>Solution:</b> Added in a vector inside the Enemy class in order to keep track of it anywhere.
6. Alien kept on stopping after one input.
><b>Solution:</b> We just put in an internal loop, as in a function inside of itself.
7. Players could go into the save file and edit it to gain unfair advantage.
><b>Solution:</b> Encrypted it, albeit not that secure, but will be better than just leaving it as it is.



