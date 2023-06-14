# 3D-tic-tac-toe
Phyton program code which allows two players to play tic-tac-toe game in 3D
The game is basically the same as regular tic-tac-toe: you try to win by getting three X’s or O’s in a row.
The trick is, instead of one grid of nine squares, you have three grids of nine squares, all stacked on top
of each other. A diagonal, horizontal, or vertical set of three lets you win, but since the game is 3-D, there
are many more winning possibilities.

Game Flow:
1. Each player enters a name
2. The first player will be chosen randomly
3. The current player will be asked to enter his move (think about how to input a move)
4. Optional - Limit the decision time of each player for 60 seconds, if 60 seconds was passed the
turn move to the next player- ( Challange create a visual representation using ascii of a progress
bar)
5. The game board will be drawn (using ascii chars)
6. Evaluation of the board for a win will be checked
7. If the game wasn’t ended (one side won or a tie) go-to step 3
8. When the game is over the winner's name will be presented
9. And a question about a new game will be asked (challenge keep track of the score of the players)
