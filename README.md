# Sea Battle

Sea Battle is a 2-player game modeled after Battleship. Players are expected to take turns guessing which spaces to fire at in order to sink their opponent's ships and win the game. The program is intended to be run on 2 separate machines at a time. Players are asked to pick their player number and then decide which player goes first in order to set up the game to run properly. The player who goes first tells the other player which space they pick, which is entered into both computers. The first player is asked whether the shot was a hit, a miss, or a sink according to the other player. This allows the game to keep track of the number of ships still remaining for each player, as well as display the opponent's spaces which have been picked on the tracking grid. The player who finds and sinks all of their opponent's ships first is the winner.

The constant GRID_SIZE on line 18 in the main.cpp file declares the size of both the primary and tracking grids, and can be changed to alter the difficulty of the game. In addition, the ship_type and ship_size vectors on lines 30 and 31 are in charge of the number and types of ships that are deployed in each game. The first vector accounts for the letters used by each ship on the grid, and the second tells how many spaces they will take up on the board. Changes to these vectors can make the game easier or harder, and when combined with the GRID_SIZE variable, the entire game difficulty can be changed for both players.

This program was a project for my CS231 class. It was completed using Dev C++, and the .dev file can be opened and browsed in the program. I completed several of the main functions, but the outline of the code was given to me by my professor, Jay Snellen. The project appears to be in full working order and as such, no additional changes are required for the game, unless the user wishes to change the difficulty using the variable and vectors mentioned above.
