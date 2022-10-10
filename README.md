# Natural Language Processing

Repositorio de la materia de Procesamiento de Lenguaje Natural de CEIA - Cohorte 5. 2022

## Word Vectorization

Word Embeddings or Word vectorization is a methodology in NLP to map words or phrases from vocabulary to a corresponding vector of real numbers which used to find word predictions, word similarities/semantics. The process of converting words into numbers are called Vectorization.

![img1](img/tfidf.png)

In this ![Notebook](clase_1/ejercicios/1a%20-%20word2vec.ipynb) we cover:
* Corpus' vocabulary
* TF-IDF
* Cosine similarity

![img2](img/cosine.jpeg)

## Simple chatbot

Basic bot that answers covid questions with DNN and Spacy.

![Notebook](clase_2/jupyter_notebooks/tensorflow/bot_spacy_covid.ipynb)

![img3](img/chatbot.jpg)

## Word Embeddings

Creation of Custom Embeddings with Gensim

![Notebook](clase_3/jupyter_notebooks/desafio_3.ipynb)

## Predict Next Word

Predict the next word in a text.

The model is trained with Charles' Dickens' books, using:
* Bidirectional LSTM layers 
* Many-to-one architecture

![Notebook](clase_4/jupyter_notebooks/desafio_4.ipynb)

![img4](img/many-to-one.png)

## Sentiment analysis with Embeddings + LSTM

Use reviews of clothing buyers to determines the evaluation of the buyer and their criticism (how many stars are assigned to the product).

![Notebook](clase_5/ejercicios/desafio_5.ipynb)

## QA bot

Use a dataset with conversations in English to build a bot to answer the user's questions. 

Using:
* LSTM
* Fasttext Embeddings

![Notebook](clase_6/ejercicios/6d_bot_qa.ipynb)