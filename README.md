# CS4500-Homework

Javascript project called 'Strange Game'. One week timeline. 

1. Randomly choose a direction: up, down, left, or right. Each direction should be equally likely, over the long haul, to be chosen.  Call the direction D.

2. Randomly choose a number of steps, either 0, 1, or 2. Each of these should be equally likely over the long haul.  Call the number of steps N.

3. Try to move the red marker N steps in the D direction. If that move would take you off the grid, go back to step 1 without moving the marker. 

4. If that move leaves you on the grid, move to the new position. If the new position happens to be the upper right hand corner of the grid, then you are done with the game (you win!).

5. It is at least theoretically possible that this game could go on for a very long time. If you have done step one 1,000,000 times, stop the game before doing step one 1,000,001, and report that situation.  
