#N-Puzzle#

##Author: Nam Duong Hoang##
###Code for the NxN-Puzzle problem###

####Description:####
The N-Puzzler is a simple program to solve N Puzzles (or NxN Puzzles). N Puzzle is a sliding block game that takes place on a *k x k* grid with *(k * k) - 1* tiles. For more info, visit https://www.hackerrank.com/challenges/n-puzzle.

####Usage:####

	nPuzzler.bat <file> <method>

N-Puzzler takes two arguments:
	1. The first refers to a text file which contains one or more n-puzzles.
	2. The second refers to the method that you want to use to solve the puzzle(s) in the above file. See Search Table for a list of valid methods.

Search Table
*Parameter*			| *Method Name*
----------------+----------
BFS							|Breadth-first Search
GBFS						|Greedy Best-first Search
DFS							|Depth-first Search
ASS							|A Star Search
HC							|Hill Climbing Search
