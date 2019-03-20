# Ultimate Tic Tac Toe Bot

AI bot for an extended version of ultimate tic tac toe. It was implemented using heuristic minimax search with alpha-beta pruning. 

## Rules

This bot plays an extended version of ultimate tic tac toe. The basic rules can be found [here](https://mathwithbaddrawings.com/ultimate-tic-tac-toe-original-post/). This version also has a few additional rules:

* Bonus move: If the player wins a small board, the player gets a bonus move. This bonus move is limited to 2 small board wins.

* Time limit: There is a time limit of 24s per move.

* Scoring: Winning the game gives the winner 86 points and the opponent 0 points. Winning the corner small boards give 4 points, center gives 3 points and remaining gives 6 points.

 ## Running the game

To see the various options: ```python2 simulator.py```
To play a game: ```python2 simulator.py <option>```