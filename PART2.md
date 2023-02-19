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

1. Major bug fixes on alien movement.
2. Implemented the alien trail, replaced the trails with game objects.
3. Implemented zombie movement.
4. Minor bug fixes on some UI : alien movement UI.
5. Implemented multiple zombies movement.
6. Implemented zombie distance calculation for zombie attack.
7. Implemented alien attack zombie.
8. Implemented zombie attack alien.
9. Print out zombie unable to attack alien when alien not in range.
10. Alien attack reset after its turn.
11. Health pack works correctly according to alien hp.
12. Arrow shown on HUD indicating which in game characters turn.
13. Added arrow command, user needs to put in correct position and direction.
14. Added quit command.
15. Improved on pod object to damage the nearest zombie.
16. Implemented the part where alien got defeated by zombie.
17. When alien got defeated by zombie, will ask user restart the game or not.
18. Added gameover function
19. Added save and load command.
20. Implemented functions to save and load game files.
21. Improved on pod object to check if zombie is defeated or not.
22. Implemented the part where zombie got defeated by alien.
23. When zombie got defeated by alien, zombie will be removed from the board and alien will continue in that direction, but sometimes it will stop. 

## <u>**Additional Features**</u>

Describe the additional features that has been implemented.

1. Alien health is changed based on number of zombies.
2. Added Encryption System to make sure the user cannot change the file without prior knowledge.
3. Added "Safety Net" to various places where it requires input from user such as Rows and Columns to avoid situation like having 0 rows or columns ***<u>(try it out)</u>***
4. A difficulty setting in which preset rows, columns and no. of zombies are set depending on which difficulty the user chose.
5. The amount of blank spaces will adjust based on amount of grids on the board to make it fair.

## <u>**Contributions**</u>

List down the contribution of each group members.

### <u>Ang Khai Pin</u>

1. Fixed some of the game UI, during alien movement and when it ends.
2. Implemented zombie movement and its UI.
3. Added additional feature 1.
4. Improved on the rock items, so when alien hits the rock, will print out which object discover.
5. Improved on the health items, so alien hp is recover accordingly.
6. Implemented multiple zombies movement.
7. Added arrow command
8. Added quit command
9. Referred to Lester's pass by reference method to implement alien attack zombie.
10. Improved on the zombie attack alien where zombie is unable to attack alien when not in range.
11. Added gameover function to implement the part where alien got defeated by zombie.

### <u>Lester Liew Jun Min</u>

1. Major bug fixes on alien movement.
2. Implemented the alien trail and when alien turns ends, object will spawn.
3. Minor bug fixes on zombie movement.
4. Implemented zombie distance calculation for zombie attack.
5. Implemented pass by reference method for zombie attack alien / alien attack zombie.
6. Implemented zombie attack alien.
7. Implemented arrow shown on HUD to show which character's turn.
8. Improved on the pod object to deal damage to nearby zombie
9. Improved on alien got defeated by zombie, reset the values for a new game.
10. Added save and load command.
11. Implemented functions to save and load game files.
12. Improved on pod object to check if zombie is defeated or not
13. Implemented the part where zombie got defeated by alien.
14. Added additional features from 2 to 5.

## <u>**Problems Encountered & Solutions**</u>

Describe the problems encountered and provide the solutions / plan for the solutions.

1. Unable to retrieve the created vector data for zombie hp, atk, range / alien hp. <br/>
><b>Solution:</b> Use pass by reference method.
2. The vectors were glitching out when doing save/load function call.
><b>Solution:</b> Found out it was due to vector size not being transferred properly, and fixed it.
3. The zombies were constantly crashing into one another and consuming each other
><b>Solution:</b> Added a bool value for if the zombies are crashing into one another, and made a function to make sure overlapping doesn't happen.
4. Alien and zombies were going out of bounds and causing ***Segfaults*** (kill me)
><b>Solution:</b> Added bool for hitBarrier to stop Alien/Zombie from moving any further.
5. Zombie numbers were going haywire after it moves.
><b>Solution:</b> Added in a vector inside the Enemy class in order to keep track of it anywhere.
6. Alien kept on stopping after one input.
><b>Solution:</b> We just put in an internal loop, as in a function inside of itself.
7. Players could go into the save file and edit it to gain unfair advantage.
><b>Solution:</b> Encrypted it, albeit not that secure, but will be better than just leaving it as it is.



