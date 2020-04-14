# NLP-application-to-classify-the-sentiment-on-Moview-Reviews
The Dataset of 25,000 movie reviews from IMDB, labeled by sentiment (positive/negative). 
Word Embedding is created and then Deep Learning used for sequential NLP.

Simple Dense Neural Networks, LSTM and GRUs followed by Bi-directional LSTMs were tried to achieve the best results in processing the reviews and classifying the sentiments provided on the movies.
Prior to application of the neural networks, word embeddings using GLoVe's 200d vectors were used to represent the numerical representation of each sequence in teh text/corpus.
Word embedding are a type of word representation that allows words with similar meaning to have a similar representation.

The Dataset of 25,000 movie reviews from IMDB, labeled by sentiment (positive/negative). Reviews have been preprocessed, and each review is encoded as a sequence of word indexes (integers).



Steps and tasks completed:
1. Import test and train data

2. Import the labels (train and test)

3. Get the word index and then Create a key-value pair for word and word_id

4. Build a Sequential Model using Keras for the Sentiment Classification task

5. Report the Accuracy of the model

6. Retrieve the output of each layer in Keras for a given single test sample from the trained model you built
