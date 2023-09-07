# 3DTicTacToe
This project highlights my 3DTicTacToe AI Project that I developed

Through using the minmax algorithm with a heuristic, the algorithm would traverse a certain number of plies down. Once the final ply was reached, if the play wasn't an end of game situation, the algorithm would use the heuristic and compute the "score" of that game state. From here the minimax algorithms would run back up the recursion stack and output the next best move for the CPU to make.

# Command Line Arguments
-first : indicates that CPU goes first\
-second : indicates that CPU goes second\
'#' : enter a number to indicate the number of plies you want the algorithm to traverse\
(The higher the number of plies, the longer the algorithm takes, but the more accurate it is).

# Run the Project
javac TicTacToe.java
java TicTacToe -first 4 (indicates CPU goes first and to traverse down 4 plies)

# Input
x : indicates what row the user wants to place their piece on.
y : indicates what column the user wants to place their piece on.
z : indicates the level (1,2,3) of which to place the piece on.

# Output
Computer will reun the algorithm and output the next game state with the CPU's move
Console will print the x,y,z of where the CPU played.
