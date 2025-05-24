# game-of-life-
this repo was made for "organizacion de computadores" final proyect 

let me explain, The Game of Life, is a cellular automaton created by John Conway, simulates the evolution of a population of cells on a grid. to see this more clearly 
lets break it down

The Grid: The game takes place on an infinite, two-dimensional grid of square cells. 

Cell States: Each cell can be either alive or dead. 

Neighbor Interaction: A cell's state in the next generation is determined by the number of its live neighbors (cells horizontally, vertically, and diagonally adjacent). 
The Rules:

    Survival: A live cell with two or three live neighbors survives to the next generation. (this is the key aspect of the game)

Death: A live cell with fewer than two live neighbors dies (underpopulation) or more than three live neighbors dies (overpopulation). 
Birth: A dead cell with exactly three live neighbors becomes alive (reproduction). 

Evolution: The rules are applied simultaneously to all cells in a generation, resulting in the next generation. 
Initial Setup: The initial pattern of live and dead cells forms the "seed" of the system, and the game evolves from there. 
