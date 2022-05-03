# Bitcoin-price-prediction-model-RNN-v-s-bidirectional-LSTM

This model takes in bitcoin transaction data from the some of the most widely used cryptocurrency exchanges around the world and predicts the bitcoin opening 
and closing price (in dollars) using Bi-directional LSTM (for opening prices) and RNN (for closing prices) which further helps in comparing the accuracy of the two models against the highly volatile bitcoin price.
The data used in this model contains Bitcoin transaction data at 1-min intervals from exchanges with higher transaction volumes, Jan 2012 to March 2021.

Results obtained from both simple RNN and bidirectional LSTMs are compared at the end. 
LSTM proves to be a better prediction algorithm for Bitcoin.
