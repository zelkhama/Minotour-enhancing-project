# Minotour-enhancing-project

The objective of this project is to explore methods and techniques to enhance Minotour (The Tourism Chatbot developped by Eurecom's D2KLab team) and improve its entities recognition. Each one of the three notebooks in this repository has a different approach 

### [Doc2vec on reviews](./Doc2vec_on_reviews.ipynb)

This notebook aims at studying the performance of Doc2vec algorithm on customers reviews scrapped from different websites. Firstly we study the similarities between the results of this method, then we study the potentiality of these results to help constructing a supervised places classifier. The data used is contained in 
[the CSV zipped file] (https://github.com/zelkhama/Minotour-enhancing-project/blob/master/cotedazur_places_full.zip) provided in the repository (the details instructions are in the notebook) 

### [Word2vec unsupervised clustering](https://github.com/zelkhama/Minotour-enhancing-project/blob/master/Word2vec%20unsupervised%20clustering.ipynb)

In this notebook we explore word2vec algorithms on large text corporas (events & places descriptions & review) to see if any insights can be found within the results. We also apply unsupervised clustering algorithms (K-means) in order to see if this can provide any additional information. 

### [Testing Rasa NLU pipeline](https://github.com/zelkhama/Minotour-enhancing-project/blob/master/Testing%20Rasa%20nlu%20pipelines.ipynb)

The notebook contains a test evaluation of Minotour on Rasa framework, for both tensorflow and spacy pipelines with increasing training data sizes. It appears that tensorflow_embedding is much faster and gives a very good accuracy while spacy has scalability problems and gives bad results. For more details, take a look at the notebook.
