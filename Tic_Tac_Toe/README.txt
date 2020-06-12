TIC TAC TOE
-------------

PROBLEM STATEMENT:-

● You now know enough to create a real program!
● Create a Tic Tac Toe game for 2 human players.
● Let’s describe what the game will be like...
● 2 players should be able to play the game (both sitting at the same computer)
● The board should be printed out every time a player makes a move
● You should be able to accept input of the player position and then place a symbol on
the board

Solution Steps:-

● We need to print a board.
● Take in player input.
● Place their input on the board.
● Check if the game is won,tied, lost, or ongoing.
● Repeat b to d until the game has been won or tied.
● Ask if players want to play again.

Step 1 : Write a function that can print out a board. Set up your board as a list, where
each index 1-9 corresponds with a number on a number pad, so you get a 3 by 3
board representation.

Step 2 :Write a function that can take in a player input and assign their marker as 'X' or
'O'. Think about using while loops to continually ask until you get a correct answer.

Step 3 : Write a function that takes in the board list object, a marker ('X' or 'O'), and a
desired position (number 1-9) and assigns it to the board.

Step 4 : Write a function that takes in a board, along with marker and checks to see if 
someone has won.

Step 5 : Write a function that uses the random module to randomly decide which
player goes first. You may want to lookup random.randint() Return a string of which
player went first.

Step 6 : Write a function that returns a boolean indicating whether a space on the
board is freely available.