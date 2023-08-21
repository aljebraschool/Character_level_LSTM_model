# Character_level_LSTM_model

This model a character-level Long Short term memory (LSTM) model with pyTorch. The network will train character by character on some text, then generate new text character by character. As an example, I will train on [Anna Karenina]([Link to Book](https://www.globalgreyebooks.com/anna-karenina-ebook.html)). This model will be able to generate new text based on the text from the book!

This network is based off of [Andrej Karpathy's](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)post on RNNs and implementation in Torch. Below is the general architecture of the character-wise RNN.
