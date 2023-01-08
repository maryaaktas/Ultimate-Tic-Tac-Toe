# UltimateTic-Tac-Toe
Ultimate Tic-Tac-Toe is a more complex version of Tic-Tac-Toe, where you are playing in a Tic-Tac-Toe that every entries are again small Tic-Tac-Toes. The player that wins in the big Tic-Tac-Toe wins the game. There is single player mode also.

The game board is a 3x3 matrix(board) where each cell of the board is also a 3x3 matrix(mini-board). Each cell of the mini-boards can be accessed by its row and column number of the board and the row and column number of the mini-boards. The board elements are 'X' and 'O'.

The choice of mini-board on which to play is not free, being determined by the opponent's previous move. The position chosen by the opponent identifies the mini-board where the game must be continued.

In addition to the normal implementation of this game, there is also a automatic player. And also the users can interrupt the game and resume it later whenever they want. The users can see last moves upto 10th last move. When the game is over, the summary of the game (every move) will be given in a text file.

You can see the details on the **'MARYA_AKTAS_Ultimate_Tic-Tac-Toe.PDF'** file, i.e., main data structures of the implementation, dynamic structures implementation, organization of the files, justification of the options, and the user manual.
