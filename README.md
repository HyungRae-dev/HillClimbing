# Titie : HillClimbing
To solve N-queen problem where N queens should be placed on a chess board(NxN) so that no queen can attack other, 
the program use steepest decent(hill climbing) algorithm. 
# Description
The whole chess board's state is represent by array(size:8) whose i-th element j represent the queen's position in the board(i,j).
The heuristic is given by counting the number of queen pair that can attack each other. 
The search start with random state and change the position of one queen so that the heuristic decrease.
# How to use
After compile the HillClimbingRandomRestart.java, execute with the number of queen you want to place. 
