# Counter4
<br>

## Rules
<br>
This is an enhanced version of the game, Connect4. The Connect 4 game is a classic strategy game that requires two players to go head-to-head in a battle to own the grid. Each player chooses either yellow or red coins and drops them into the grid, starting either in the middle or at the edge, to stack their colored coins upwards, horizontally, or diagonally. The strategy comes into play when players aim to block their opponents while trying to be the first to get four of their colored coins in a row to win. 
<br>
<br>
In our game, all the rules are the same, except for an additional rule. That is, after the 6th turn, one random previously input coin of the player who started the game will turn to his opponents. For example, if Player X started the game, after the 6th turn, one of his coins will change to Player O's. See the diagram below to get a better idea (the human input was in column 2 row 2, but the random change was done in column 2, bottom row). 
<br>

![Screenshot 2023-11-24 193618](https://github.com/cdfelixj/Counter4/assets/120282157/857bed1e-e7b6-404c-8a41-f54521c0f0ec)

In the 7th turn, the same thing happens, but this time in favor of Player X. After the 7th move (assuming it's Player O's turn), one coin of Player O will turn to Player X's. See the diagram below for better understanding (the computer input was in column 4, bottom row 2, but the random change was done in column 2, bottom row 2).
<br>

![Screenshot 2023-11-24 193618](https://github.com/cdfelixj/Counter4/assets/120282157/c710f427-3a72-49fe-a9cc-7ec8a190fe53)

This process of switching coins continues until a winner is found or the match is tied (the board is full). 
<br>

## Different Approaches
<br>
We have developed 3 bots with different functions. At first, there is a bot that prioritizes blocking rather than winning. We named that bot 'Defensive bot'. Then there is another bot named 'Aggressive bot' that prioritizes winning rather than blocking and lastly the 'Neutral bot' is the one that plays normally. It sees if any possible 4th input blocking can be done, if not then it goes for stacking if there are 3 or 2 same computer inputs.
<br>
We have run many bots vs bots simulations and found out that the winner selection is a bit random. Unlike CONNECT4, where there is a comparative advantage for the Neutral bot, here in Counter4, it's a bit more fair. We have seen that the Aggressive bot wins against the Defensive bot and the Neutral wins against the Defensive. Now you may think that the Neutral has an absolute advantage in winning.
<br>

### But you are wrong! 
<br>
The Neutral bot loses against the Aggressive one! And that's what makes our game unique and fair.

## Please give it a try and let us know if we can improve it. (I'm sure there are so many things we need to improve!) Thank you.

