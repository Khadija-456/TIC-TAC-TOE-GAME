Tic Tac Toe Game with Minimax AI (SFML)
This is a C++ project where a human plays Tic Tac Toe against a computer. The game uses SFML for graphics and the Minimax algorithm for AI decision-making.

Features
Human vs Computer
You play as 'X'. The computer plays as 'O'.

Minimax AI
The computer uses the Minimax algorithm with a game tree to make smart moves. It tries to win or force a draw.

Undo Functionality
Press U to undo your move and the computer's move.

Graphical Interface
The game is displayed using SFML graphics. The grid and moves are drawn clearly.

Winner/Draw Detection
The game detects if someone has won or if the game is a draw.

Code Structure
Board: A 3x3 grid using characters ('X', 'O', '*')

Move History: A linked list stores all moves to support undo.

Game Tree: A tree structure is used for evaluating all possible game states.

Minimax: The AI recursively calculates the best possible move.

SFML Drawing: Uses RectangleShape and Text to draw grid and symbols.

Requirements
C++ compiler (g++, Visual Studio, etc.)

SFML library installed

Font file: ARIAL.ttf (must be placed in the same folder or correct path)

How to Run
Make sure SFML is properly set up.

Place ARIAL.ttf in the folder.

Compile and run main.cpp.

Click a cell to place 'X'.

Press U to undo.

The game ends when someone wins or it's a draw.

Summary
Language: C++

Graphics: SFML

AI: Minimax

Extras: Undo, Win/Draw 