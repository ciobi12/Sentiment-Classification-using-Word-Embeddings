# Sentiment-Classification-using-Word-Embeddings

Using Deep Learning techniques, I implemented a system that tries to classify the sentiment based on a person's movie review. Here, sentiments are labeled as 1: the person likes the movie and 0: the person doesn't like the movie. When testing the network, it assigns a number from 0 to 1 to the predicted reviews. 

***

The Deep learning text classification model architecture generally consists of the following components connected in sequence:

* Embedding Layer: Word Embedding is a representation of text where words that have the same meaning have a similar representation. In other words it represents words in a coordinate system where related words, based on a corpus of relationships, are placed closer together.

* Recurrent layer: it takes the sequence of embedding vectors as input and converts them to a compressed representation. The compressed representation effectively captures all the information in the sequence of words in the text. This layer usually consists of a LSTM (Long Short-Term Memory) or a GRU (Gated Recurrent Unit).

* Fully Conected Layer: it takes the deep representation from the LSTM/GRU and transforms it into the final output classes or class scores. This component is comprised of fully connected layers along with batch normalization and optionally dropout layers for regularization. The activation function usually consists of softmax or sigmoid. 
