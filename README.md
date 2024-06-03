# Tic_Tac_Toe
Simple tic-tac-toe game project using python

The tic-tac-toe game is for two players. One player plays X and the other plays O. The players take turns placing their marks on a grid of three-by-three cells. If a given player gets three marks in a row horizontally, vertically, or diagonally, then that player wins the game. The game will be tied if no one gets three in a row by the time all the cells are marked.

With these rules in mind, you’ll need to put together the following game components:

The game’s board, which you’ll build with a class called TicTacToeBoard
The game’s logic, which you’ll manage using a class called TicTacToeGame
The game board will work as a mix between view and controller in a model-view-controller design. To build the board, you’ll use a Tkinter window, which you can create by instantiating the tkinter.Tk class. This window will have two main components:

Top display: Shows information about the game’s status
Grid of cells: Represents previous moves and available spaces or cells
You’ll create the game display using a tkinter.Label widget, which allows you to display text and images.

For the grid of cells, you’ll use a series of tkinter.Button widgets arranged in a grid. When a player clicks one of these buttons, the game logic will run to process the player’s move and determine whether there’s a winner. In this case, the game logic will work as the model, which will manage the data, logic, and rules of your game.
