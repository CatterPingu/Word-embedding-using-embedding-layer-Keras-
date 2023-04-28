# Word-embedding-using-embedding-layer-Keras-

This is a simple example of word embedding using TensorFlow-Keras.

The code starts by importing the necessary modules. We then define our list of sentences and initialize the size of our vocabulary. Next, we create a one-hot representation of our sentences using the one_hot function. We then pad the sequences to ensure that all sentences are of equal length.

Afterwards, we define the dimensionality of our embeddings and build our model using the Embedding layer. We compile the model using the Adam optimizer and mean squared error as the loss metric. Finally, we print out the summary of the model and see how the words have been converted into featurized vectors.

## Conclusion

In this example, we have shown how to preprocess text data and create word embeddings using TensorFlow-Keras. These embeddings can be used as inputs to train machine learning models for various natural language processing tasks.
