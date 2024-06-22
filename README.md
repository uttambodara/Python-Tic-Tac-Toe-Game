# Python-Tic-Tac-Toe-Game
Tic-tac-toe is a very popular game, so let’s implement an automatic Tic-tac-toe game using Python. The game is automatically played by the program and hence, no user input is needed. Still, developing an automatic game will be lots of fun. Let’s see how to do this. NumPy and random Python libraries are used to build this game. Instead of asking the user to put a mark on the board, the code randomly chooses a place on the board and put the mark. It will display the board after each turn unless a player wins. If the game gets drawn, then it returns -1. 

Explanation: play_game() is the main function, which performs the following tasks :

Calls create_board() to create a 3×3 board and initializes with 0.
For each player (1 or 2), calls the random_place() function to randomly choose a location on board and mark that location with the player number, alternatively.
Print the board after each move.
Evaluate the board after each move to check whether a row or column or diagonal has the same player number. If so, displays the winner’s name. If after 9 moves, there is no winner then displays -1.
