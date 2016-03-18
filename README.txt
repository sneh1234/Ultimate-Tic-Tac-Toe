A 9X9 Tic-Tac-Toe game written in python and works with Artificial intelligence. It works on alpha beta pruning and heuristics.
 
How it differs from simple tic tac toe:
1) In this game a 9X9 board is used.
2) Let us say 3X3 matrices as block . So if a player make a move in top left cell of that block then the next player can move top left 3 blocks,and similary for other positions.
For example let us index blocks from 1 to 9 as:
	 1 2 3
	 4 5 6
         7 8 9          
   and player played in top left position of block 5 now next player can only make a move in 1, 2 and 4 blocks and similary for other blocks.


How it works:
         A utility function is calculated based on heuristic and alpha beta search is done till depth 4. So it selects the best possible option from available blocks. 
                                             
