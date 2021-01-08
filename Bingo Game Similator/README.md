A Bingo card consists of 5 columns of 5 numbers which are labelled with the letters
B, I, N, G and O. There are 15 numbers that can appear under each letter. In particular,
the numbers that can appear under the B range from 1 to 15, the numbers that can
appear under the I range from 16 to 30, the numbers that can appear under the N
range from 31 to 45, and so on.

The first function creates a random Bingo card and stores it in a dictionary. The
keys will be the letters B, I, N, G and O. The values will be the lists of five 
that appear under each letter. The second function displays the Bingo card
with the columns labelled appropriately.

A winning Bingo card contains a line of 5 numbers that have all been called. Players
normally record the numbers that have been called by crossing them out or marking
them with a Bingo dauber. 

In this project I wrote a program that simulates a game of Bingo for a single
card. It begins by generating a list of all of the valid Bingo calls (B1 through O75).
Once the list has been created it randomizes the order of its elements by calling
the shuffle function in the random module. Then program consumes calls out of the 
list and cross out numbers on the card until the card contains a winning
line. At the end main program asks if the user wants to continue.
