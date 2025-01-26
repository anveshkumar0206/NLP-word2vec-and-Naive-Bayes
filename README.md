# NLP-with-word2vec-and-Naive-Bayes

Project Overview

This project explores Natural Language Processing (NLP) concepts using Word2Vec embeddings and a Naïve Bayes classifier for text classification. 

The tasks include:
1.Loading GloVe Word2Vec embeddings for word similarity analysis.
2.Computing word similarity scores between different word pairs.
3.Solving word analogy problems using vector arithmetic in the embedding space.
4.Applying a Naïve Bayes classifier for spam detection using the Spam-Ham dataset.

Dataset
The project works with:
GloVe Word2Vec embeddings from Wikipedia,
Spam-Ham dataset for text classification.

NLP Tasks

1.Word Similarity Computation
Using pre-trained GloVe embeddings, compute similarity scores for word pairs such as:
Man vs. Woman
Chair vs. Throne
Water vs. Baby

2.Word Analogies Using Word2Vec
Solve analogy problems like:
King is to Queen as Man is to ___?
Princess is to Prince as Woman is to ___?
A child is to an adult as ___ is to a woman?

3.Spam Detection Using Naïve Bayes Classifier
Train a Naïve Bayes classifier on the Spam-Ham dataset.
Predict whether a given text message is spam or not.
Evaluate the classifier's accuracy.

Model Training & Evaluation:
The Word2Vec model computes cosine similarity between word vectors.
The Naïve Bayes classifier is trained on a labeled dataset to classify spam messages.

Results
Displays word similarity scores using Word2Vec.
Shows the most relevant analogies from the dataset.
Outputs spam classification results.

References:
GloVe Word Embeddings,
Word2Vec Documentation, and
Naïve Bayes Classifier in NLP
