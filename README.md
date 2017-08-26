## A slow Boggle with Python.
A slow verion of boggle which will be broken down by creating a grid, using a dictionary file, creating our search algorithm and connecting neighbours.
For a faster version look at boggle2 repository which will be added in the near future. Boggle2 will increase algorithm efficiency and use sets rather than lists and use sclicing notation to create wrod stems.


# THE GRID

We need to store a set of letters in a grid arrangement. So, we need to store the positions of the grid, and the letter at each position.


# THE DICTIONARY

We will load a list of words from a dictionary file. When we string together a sequence of letters on the board, we need to be able to quickly search the dictionary to determine if it’s a word.


# THE SEARCH ALGORITHM

At this point we don’t need to concern ourselves with the specifics of how our algorithm will work, but it should be obvious that if we have a grid and a list of valid words, we have all the inputs we need.


# NEIGHBOURS

The rules of Boggle state that a letter can be connected with any of it’s neighbours, vertically, horizontally, or diagonally. We are going to need a way to identify the neighbours of any given position on the grid.

Our planning at this point does not need to be any more detailed this. Obviously the more carefully we think through our ideas, the easier it should be to implement them.

However there are diminishing returns. It can be difficult to think about a programming problem in an abstract way. Sometimes we can get clarity more quickly by writing some code and experimenting.

