# Text Genration with LSTM - Next word predictor

This is a simple and basic text generation project using Long Short-Term Memory (LSTM) networks. The model is trained to predict the next word in a sequence of text based on the previous words. Kaggle API key was used to import the dataset, and the model was trained for 15 epochs.

## Introduction to LSTMs

Long Short-Term Memory (LSTM) networks are a type of recurrent neural network (RNN) architecture designed to overcome the vanishing gradient problem of traditional RNNs. They are well-suited for processing and making predictions on sequences of data, such as time series data, natural language text, and more.

LSTMs have a memory cell that can maintain information over long periods of time, allowing them to capture dependencies and patterns in sequences with variable time steps. They achieve this by using gates that regulate the flow of information into and out of the memory cell, including an input gate, forget gate, and output gate. These gates, along with the cell state, enable LSTMs to selectively update and forget information, making them powerful tools for modeling sequential data.

For a more in-depth understanding of LSTMs, I recommend reading the following resource: [Understanding LSTM Networks](https://colah.github.io/posts/2015-08-Understanding-LSTMs/)

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/shikhar5647/Next_word_predictor_LSTM.git
