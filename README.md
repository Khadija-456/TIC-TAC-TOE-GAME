🎮 Tic Tac Toe Game with Minimax AI(SFML)
This project is a Tic Tac Toe game developed in C++ using the SFML(Simple and Fast Multimedia Library).It allows a human to play against a computer that uses the Minimax algorithm to make smart moves.

📌 Main Features
✅ Human vs Computer
You play as X.The computer plays as O.The game is turn - based.

🧠 Computer AI(Minimax)
The computer uses the Minimax algorithm with a game tree to evaluate the best possible moves and counter your choices.It always tries to either win or force a draw.

🔁 Undo Functionality
You can undo the last two moves(your move and the computer's move) by pressing the U key. This is helpful if you want to try a different strategy.

	🖼️ Graphical Interface(SFML)
	The game uses SFML to draw the game window, the grid, and X / O symbols.It's simple and easy to understand.

	🏁 Winner & Draw Detection
	The game automatically detects :

If the human has won

If the computer has won

If the board is full(draw)

🧱 How the Code Works
1. Board Setup
The board is a 3x3 grid.Each cell can contain :

'X' for human

'O' for computer

'*' for empty

2. Move History
A custom class stores all the moves using a linked list.It allows going back(undo) by removing the last two moves.

3. Game Tree Node
Every possible state of the board is represented as a node.The computer builds this tree to explore all possible future moves and outcomes.

4. Minimax Algorithm
This function checks all possible moves and :

Gives a high score if the computer can win

Gives a low score if the human might win

Picks the best move using recursion

5. SFML Drawing
A window is created using SFML.

Grid lines are drawn using RectangleShape.

Player moves(X / O) are shown using SFML Text with a loaded font.

Winner or draw message is displayed after the game ends.

🖥️ Requirements
To run this game, you need :

A C++ compiler(like g++, Visual Studio, or Code::Blocks)

SFML library installed and linked properly

A font file like ARIAL.ttf(used to display the X / O and game messages)

🗂️ File Structure
main.cpp        → Contains the full game logic and SFML code
ARIAL.ttf       → Font file used to display text
README.md       → This file
📍 Make sure you put the font file in the correct folder as mentioned in the code, or change the path inside the code.

📋 How to Play
Run the game.

Click on any empty cell to place your X.

The computer will automatically place an O in response.

If you press U, your last move and the computer's move will be undone.

The game ends when :

Someone gets 3 in a row(horizontal, vertical, or diagonal)

Or the board is full and no one wins(draw)

🎨 Font Note
In the code, this line is used to load the font :


font.loadFromFile("ARIAL.ttf");

🎯 Tips
The AI is smart — it's very hard to beat because of the Minimax algorithm!

If you're learning, try changing the AI logic to make it easier or explore how Minimax works by printing scores.

Undo is helpful for experimenting with different moves.

👩‍💻 Tool used

C++ programming

Game development with SFML

Artificial Intelligence using Minimax

Data structures like linked lists and trees

✅ Summary
Language : C++

Graphics Library : SFML

AI Logic : Minimax with game tree

Extras : Undo functionality, win / draw detection

This is a great project to understand how game AI works and how to use SFML for making graphical games.