# Connect4AI

It is a digital version of the board game called Connect4 developed with Aritifical intelligence.  <br/>
Algorithms used in the game are "minmax" and "alpha beta pruning". 								   <br/>
The game is developed using python programming language with the pygame module.					   <br/>

## List of Python Libraries used :-
--> Numpy
--> Pygame

## Scoring Mechanism for AI

### Player Scoring
--> Center Column     +4                                                							<br/>
--> Lines of Two      +2 (for each direction, left, right and diagonal) 							<br/>
--> Lines of Three    +5 (for both direction, left and right)           							<br/>
--> (Connect 4) Win!  +1000 (VERY LARGE SCORE)                          							<br/>

### Opponent Scroing
--> Lines of Two      -2 (for each direction, left, right and diagonal) 							<br/>
--> Lines of Three    -100 (for both direction, left and right)         							<br/>
