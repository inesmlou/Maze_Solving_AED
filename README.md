# Maze_Solving_AED

Project of the course Algorithms and Data Structures.

The goal is to find the optimal path between a start and an end point of a maze. The optimal path corresponds to the one with the smallest cost.
Each cell of the maze can be of one of three types: 
	- black) impossible to pass
	- grey) correspond to doors that have a certain cost to open
	- white) free cell that has no cost to pass
The output of the problem should be the sequence of doors (grey cells) that need to be open to arrive to the finish cell with smallest cost.
The maze is described in the input file, and includes the description of the maze dimensions and of which kind is each of the cells. 
The maze can be of three kinds:
	- unsolvable, if there is no path that allows going from the start cell to the finish one respecting the game rules
	- solvable without any cost - in which any doors needs to be open to arrive at the finish cell
	- solvable with multiple solutions, that is, different paths with the same cost lead to the finish cell, in which any of them is considered correct.


