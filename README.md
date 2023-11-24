# Counter4
<br>
## Rules
<br>
This is an enhanced version of the game, Connect4. The Connect 4 game is a classic strategy game that requires two players to go head-to-head in a battle to own the grid. Each player chooses either yellow or red coins and drops them into the grid, starting either in the middle or at the edge, to stack their colored coins upwards, horizontally, or diagonally. The strategy comes into play when players aim to block their opponents while trying to be the first to get four of their colored coins in a row to win. 
<br>
In our game, all the rules are the same, except for an additional rule. That is, after the 6th turn, one random previously input coin of the player who started the game will turn to his opponents. For example, if Player X started the game, after the 6th turn, one of his coins will change to Player O's. See the diagram below to get a better idea (the human input was in column 2 row 2, but the random change was done in column 2, bottom row). 
<br>

![Screenshot 2023-11-24 193618](https://github.com/cdfelixj/Counter4/assets/120282157/857bed1e-e7b6-404c-8a41-f54521c0f0ec)

In the 7th turn, the same thing happens, but this time in favor of Player X. After the 7th move (assuming it's Player O's turn), one coin of Player O will turn to Player X's. See the diagram below for better understanding (the computer input was in column 4, bottom row 2, but the random change was done in column 2, bottom row 2).
<br>

![Screenshot 2023-11-24 193618](https://github.com/cdfelixj/Counter4/assets/120282157/c710f427-3a72-49fe-a9cc-7ec8a190fe53)

This process of switching coins continues until a winner is found or the match is tied (the board is full).


| Attempt | #1    | #2    |
| :---:   | :---: | :---: |
| Seconds | 301   | 283   |
