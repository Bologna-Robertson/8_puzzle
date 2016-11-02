# 8_puzzle

This program solves the 8-puzzle problem using the "A*" search algorithm. The Board.java constructor receieves an N-by-N array containing N^2 integers between 0 and N^2 - 1, where 0 represents the blank square. This implementation supports all Board methods in time proportional to N^2 (or better) in worst case, with the exception that isSolvable() may take up to N^4 in the worst case.
