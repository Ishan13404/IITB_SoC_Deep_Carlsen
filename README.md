# IITB SoC'23 Deep Carlsen

## Description

The project aims at building a chess engine model using Deep Learning unlike the traditional ways of brute force game theoretic algorithms. This is a Chess Engine built using deep learning techniques to evaluate chess positions and make optimal moves. The engine uses a neural network model to predict the evaluation scores for different positions on the chessboard and selects the best move based on the predicted scores.

## Features

- Evaluation Function: The engine uses a deep neural network model to evaluate the strength of different chess positions. The model takes the current board state as input and outputs an evaluation score. The evaluation function is trained on a large dataset of chess positions and scores.

- Move Selection: The engine uses the minimax algorithm with alpha-beta pruning to search through the possible moves and select the best move for the current position. The minimax algorithm, combined with the neural network evaluation, helps the engine make informed and strategic moves.


## Usage

1. Open  <code>model.ipynb</code> 

2. Run each code block in the same order as mentioned in the notebook.

3. Let the model train for some time (it may take upto several hours.)

4. Enter your own test chess position (in the form of fen id) or use the existing test example.

5. The engine gives the predicted value of the evaluation function of that position.

6. Run the subsequent code blocks to make the engine predict the best move.

## Acknowledgments

- The implementation of the Chess Engine is based on the guidance and inspiration from various online resources and tutorials.
- Special thanks to the developers of the python-chess library for providing a convenient interface to work with chess positions and moves.
- A big thankyou to my SoC'23 Mentors <B>Navyansh Mahla</B> & <B>Atishay Jain</B> for their valuable guidance and support.

# Made By
Ishan Grover (Roll No.- 22B1528)

## Contact
For any inquiries or questions, please contact ishangrover13404@gmail.com.
