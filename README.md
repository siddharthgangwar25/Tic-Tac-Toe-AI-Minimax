What is Tic-Tac-Toe? 

Tic-tac-toe, noughts and crosses, or Xs and Os is a game for two players who take turns marking with symbols the spaces in a 
3×3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row is the winner. 
In this project, the opponent is the computer.

Algorithm : Minimax

Minimax is a artificial intelligence applied in two player games, such as tic-tac-toe, checkers, chess and go. 
This games are known as zero-sum games, because in a mathematical representation: one player wins (+1) and other player 
loses (-1) or both of anyone not to win (0).

How does Minimax work?

The algorithm recursively search the best move, that leads the Max player to win or draw. It considers the current state of the game and available moves at that state, then for each valid move, it plays (alternating min and max) until it finds a terminal state.

Instructions for Game

1. Enter ‘x’ or ‘o’ to choose which symbol you want to play.

2. Enter if you want to play first, ‘y’ for yes or ‘n’ for no.



3. Play by entering the number of the cell you want to put your symbol in.

4. If all the cells are filled and no one put three of their symbols in a horizontal, vertical, or diagonal row, then game is draw. In the other case, it outputs the winner.
