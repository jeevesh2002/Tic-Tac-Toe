# Tic-Tac-Toe
<h2>Implemented an AI to play Tic-Tac-Toe optimally using Minimax algorithm.</h2>
<h1><bold>Getting Started</bold></h1>
<ul>
  <li>Download the distribution code from the repo and unzip it.</li> 
  <li>Once in the directory for the project, run pip3 install -r requirements.txt to install the required Python package (pygame) for this project.</li>
  <li>Run python runner.py</li>
</ul>

<h1><bold>Understanding</bold></h1>
  <p>There are two main files in this project: runner.py and tictactoe.py. tictactoe.py contains all of the logic for playing the game, and for making optimal moves. runner.py contains all of the code to run the graphical interface for the game. You should be able to run python runner.py to play against your AI!

Let’s open up tictactoe.py to get an understanding for what’s provided. First, we define three variables: X, O, and EMPTY, to represent possible moves of the board.

The function initial_state returns the starting state of the board. For this , I have chosen to represent the board as a list of three lists (representing the three rows of the board), where each internal list contains three values that are either X, O, or EMPTY.</p>
