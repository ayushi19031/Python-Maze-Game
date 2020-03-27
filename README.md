# Python-Maze-Game
Efficient use of classes and objects to implement a maze game in python

# PURPOSE  
This is a game in python using classes and objects. It is a grid of size(n*n) and n is to be taken as an input from the user. The player gies an input of a command which is a string. The string is spilt to decode the list of moves for the player. The player can move up, down, left or right in the grid and can rotate the grid clockwise or anticlockwise. There is a record of score which is calculated. If the player hits an obstacle, his score is decreased. If the player hits a number in the grid, his score increases. If the player is able to reach final cell of grid, he wins, else he loses. The project has been more elaborately explained in the attached pdf labelled as game_description.
  
# Python Modules used
1. os module  
2. copy module  
3. time module  
4. random module  

# How to play?
1.User runs the python file on the command terminal.  
2. The User will enter an integer. The program will display a grid of that size with starting position, ending position, randomly generated obstacles and numbers(to increase points).  
3. Then the user enters a string of moves. Say, "L3R6A3C2U4D2". L is for left, R for right, U for up, D for down. C is to rotate the grid clockwise and A for anticlockwise. The number after each letter denotes how many times operation has to be performed.  
4. If after executing the whole string, the player reaches the end destination, he wins. Else he loses.  

--Extensive application of the concept of classes, objects and methods.

Further improvements possible:
Use of tkinter module and pygame module to make the game have animative features and more good looking and allow interaction other than giving a text input.
