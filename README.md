# Counter4
<br>
## Rules
<br>
This is an enhannced version of the game, Connect4. The Connect 4 game is a classic strategy game that requires two players to go head-to-head in a battle to own the grid. Each player chooses either yellow or red coins and drops them into the grid, starting either in the middle or at the edge, to stack their colored coins upwards, horizontally, or diagonally. The strategy comes into play when players aim to block their opponents while trying to be the first to get four of their colored coins in a row to win. 
<br>
In our game, all the rules are same, except for an additional rule. That is, after the 6th turn, one random previously input coin of the player who started the game will turn to his opponents. For example, if Player X started the game, after the 6th turn, one of his coins will change to Player O's. See the diagram below to get a better idea (the human input was in column 2 row 2, but the random change was done in column 2, bottom row). 

  1   2   3   4   5   6   7             [The next step is done by the bot]
+---+---+---+---+---+---+---+            
|   |   |   |   |   |   |   | 
+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   | 
+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   | 
+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   | 
+---+---+---+---+---+---+---+
| O |   | O |   |   |   |   | 
+---+---+---+---+---+---+---+
| X | X | X | O |   |   |   | 
+---+---+---+---+---+---+---+
  1   2   3   4   5   6   7
Player X, choose a column (1-7):  2      [This step is done by human]
+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   | 
+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   | 
+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   | 
+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   | 
+---+---+---+---+---+---+---+
| O | X | O |   |   |   |   | 
+---+---+---+---+---+---+---+
| X | O | X | O |   |   |   | 
+---+---+---+---+---+---+---+
  1   2   3   4   5   6   7
In the 7th turn, the same thing happens, but this time in favour of player X. After the 7th move (assuming it's player O's turn), one coin of Player O will turn to Player X's. See the diagram below for better understanding (the computer input was in column 4, bottom row 2, but the random change was done in column 2, bottom row 2).

Player X, choose a column (1-7):  2      [This step is done by human]
+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   | 
+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   | 
+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   | 
+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   | 
+---+---+---+---+---+---+---+
| O | X | O |   |   |   |   | 
+---+---+---+---+---+---+---+
| X | O | X | O |   |   |   | 
+---+---+---+---+---+---+---+
  1   2   3   4   5   6   7              [The next step is done by the bot]
+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   | 
+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   | 
+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   | 
+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   | 
+---+---+---+---+---+---+---+
| O | X | X | O |   |   |   | 
+---+---+---+---+---+---+---+
| X | O | X | O |   |   |   | 
+---+---+---+---+---+---+---+
  1   2   3   4   5   6   7 


| Attempt | #1    | #2    |
| :---:   | :---: | :---: |
| Seconds | 301   | 283   |
