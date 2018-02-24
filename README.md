# ConnectFour
------------------------
Also known as Captain's Mistress, Four Up, Plot Four, Find Four, Four in a Row, Four in a Line and Gravitrips (in Soviet Union

As per wikipedia link, Rules are : 
It is a two-player connection game in which 
  the players first choose a color and then take turns dropping colored discs from the top into a seven-column, 
  
[ Note : six-row vertically suspended grid. The pieces fall straight down, occupying the next available space within the column.]

Rule : form a horizontal, vertical, or diagonal line of four of one's own discs. Connect Four is a solved game. 
The first player can always win by playing the right moves.
https://en.wikipedia.org/wiki/Connect_Four

Ignoring Animated UI, This includes Terminal Game:
------------------------------------------------------------------------
This project includes a functional subset of the code for the game board, game pieces, and player state. The code should include functions to place a piece into the game board and check if one of the players has won the game. It should simulate the turns taken by players (in other words, you do NOT have to collect actual input from players, so you should not build UI to do so).

The code should also include a function to print out the board, in ASCII. For example, here is a plausible print out after two turns - one from player 'X' and player 'O':

> python3 ConnectFour.py
>
 1   2   3   4   5   6  
 *   *   *   *   *   *  
 *   *   *   *   *   *  
 *   *   *   *   *   *  
 *   *   *   *   *   *  
 *   *   *   *   *   *  
 *   *   *   *   *   *  
.................................................. 
Preference :  A  SEQ :  1
.................................................. 
A  turn >>>>>......................... 
Please select X or O > X
Please Enter column Number >4
 1   2   3   4   5   6  
 *   *   *   *   *   *  
 *   *   *   *   *   *  
 *   *   *   *   *   *  
 *   *   *   *   *   *  
 *   *   *   *   *   *  
 *   *   *   X   *   *  
.................................................. 
Preference :  B  SEQ :  2
.................................................. 
B  turn >>>>>......................... 
Please select X or O > 
.
.
.................................................. 
Preference :  B  SEQ :  10
.................................................. 
B  turn >>>>>......................... 
Please select X or O > X
Please Enter column Number >1
 1   2   3   4   5   6  
 *   *   *   *   *   *  
 *   *   *   *   *   *  
 X   *   *   *   *   *  
 O   X   *   *   *   *  
 O   O   X   *   *   *  
 O   X   X   X   *   *  
.................................................. 
User :  B  Win the Match by  5.0  Steps
.................................................. 
