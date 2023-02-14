
# Utilizing Multi-Layer Networks for Tic-Tac-Toe Move Prediction

This project aims to utilize multi-layer neural networks (MLN) for predicting the next move in a game of Tic-Tac-Toe.

## Approach for Training Data Creation
The training data was created by simulating a large number of Tic-Tac-Toe games. At each turn, the current state of the board was used as input features and the next move was recorded as the corresponding label. The collected data was split into training and testing sets and was used to train the MLN.

## Tic-Tac-Toe Man vs. Machine Application
An application was developed to play a game of Tic-Tac-Toe between a human player and the machine. The decision made by the machine is the result predicted by the MLN. The MLN takes in the current state of the board and outputs the predicted next move. The game continues until a win or draw is declared.

By using this approach, the MLN is able to learn from its past experiences and make more informed decisions as it plays more games. This allows for a more challenging and dynamic Tic-Tac-Toe experience.
