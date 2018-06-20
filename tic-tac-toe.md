# Tic-tac-toe
## Contents
* [What is Tic-tac-toe?](What-is-Tic-tac-toe?)
* [Possible Outcomes](Possible-Outcomes)
* [How to Play?](How-to-Play?)

## What is Tic-tac-toe?

Tic-tac-toe is a game for two players, where a player who marks (either X or O) a complete row on a 3x3 grid will win the game. A player can mark the row either horizontally, vertically or diagonally.

## Possible Outcomes
* Win: A player who marks a complete row wins the game.
* Draw: The game can be declared as Draw if a complete row is not marked.

## How to Play?
The following example illustrates one of the possible ways to play on a 3x3 grid. In this example, Player 1 marker is X and Player 2 marker is O.

   ` 1  2  3`
 
   `4  5  6`
 
   `7  8  9`

* Step 1: 
  * Player 1: **5** (the mark at the center can connect all rows. Therefore, marking 5 is the optimum choice.)
  * Player 2: **9** (player 2 can mark anywhere considering to link the row in the subsequent steps.)
* Step 2: 
  * Player 1: As 1-5-9 combination is ruled out, player 1 can select any of the following combinations:
    * 2-5-9
    * 3-5-7 
    * 4-5-6
  * Player 2: Similarly, player 2 can mark to prevent player 1 from marking X in row.
* Repeat Step 2 until all unmarked grids are marked. 






