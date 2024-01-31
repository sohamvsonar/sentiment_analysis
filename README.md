# Sentiment Analysis with Smoothed Bigram Language Model

This repository contains Python code for sentiment analysis using a smoothed bigram language model. The model is trained on the Stanford Sentiment Treebank (SST-2) dataset. It predicts the sentiment of movie reviews as either positive or negative.

## Introduction

This script aims to provide insights into text data using Natural Language Processing (NLP) techniques.

With the goal of providing accurate sentiment predictions, the script calculates the prior probabilities, vocabulary size, log probabilities, and accuracy of the model. By employing techniques such as alpha smoothing, the model effectively handles unseen word combinations and enhances its predictive capabilities.

By training on a labeled dataset and evaluating its performance, this script serves as a valuable tool for sentiment analysis tasks, enabling users to understand the overall sentiment conveyed.

The script utilizes the SST (Stanford Sentiment Treebank) dataset obtained from the [GLUE Benchmark](https://gluebenchmark.com/tasks).
 
## Dependencies

- Python 3.12
- pandas
- NLTK (Natural Language Toolkit)

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/sohamvsonar/sentiment_analysis.git

2. Install the dependencies:
    ```bash
    pip install nltk

3. Run the script:
    ```bash
    python sentiment_analysis.ipynb
