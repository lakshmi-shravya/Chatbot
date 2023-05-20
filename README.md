# An Interactive NLP-based AI System

## Datasets
* small_talk.json - contains the questions and answers for a simple small talk https://github.com/microsoft/botframework-cli/blob/main/packages/qnamaker/docs/chit-chat-dataset.md#chit-chat-using-qna-maker
* refined_dataset.csv - contains 4614 entries of English language movies from 2000-2017. The data is a subset of the wikipedia_plots.csv from the Kaggle https://www.kaggle.com/jrobischon/wikipedia-movie-plots

## Pre-processed Data
Preprocessing the movie plots for movie recommnedation is very time consuming so I pickle files can be generated for the bag of words and the vocabulary for the plots from refined_dataset.csv
* bow.pickle =  bag of words dictionary
* vocab.pickle - vocabulary list

## Chat Bot
The complete implementation of the chatbot with three features: small talk, movie information queriying and assitance with ticket booking can be found in Chatbot.ipynb
