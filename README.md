# Topic Modeling on News Articles using LDA

## Overview
This project implements an end-to-end topic modeling pipeline using Latent Dirichlet Allocation (LDA) on BBC news articles.

## Steps
- Text preprocessing (tokenization, stopword removal, lemmatization)
- Dictionary and corpus creation using Gensim
- Topic modeling using LDA
- Topic evaluation using coherence score
- Topic visualization using pyLDAvis

## Tools & Libraries
- Python
- Gensim
- spaCy
- pyLDAvis
- Matplotlib

## Dataset
BBC News Dataset (Kaggle)

## Results
The optimal number of topics was selected using coherence score, and meaningful topics such as Politics, Sports, Business, Technology, and Entertainment were discovered.
