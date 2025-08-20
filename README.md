## Review Analysis and Topic Modeling

This repository contains a Python-based project for analyzing product reviews using sentiment analysis and topic modeling techniques.

## Overview

The project performs the following tasks:
- Cleans and preprocesses review text
- Classifies sentiment using TextBlob
- Extracts topics using Latent Dirichlet Allocation (LDA)
- Visualizes sentiment distribution and topic keywords

## Dataset

- Source file: Reviews.csv  
- Column used: Text (renamed to "review")  
- Missing values are removed

## Installation

Required Python libraries include:
- nltk
- textblob
- wordcloud
- matplotlib
- seaborn
- scikit-learn
- pandas

Additional NLTK resources used:
- punkt
- stopwords
- wordnet

## Preprocessing Steps

- Convert text to lowercase  
- Tokenize using regular expressions  
- Remove stopwords  
- Apply lemmatization

## Sentiment Classification

Sentiment is determined using TextBlob polarity scores:
- Positive: polarity greater than 0.1  
- Negative: polarity less than -0.1  
- Neutral: between -0.1 and 0.1

## Topic Modeling

- Text is vectorized using CountVectorizer  
- LDA is applied to extract four topics  
- Top ten keywords are displayed for each topic

## Visualizations

- Bar chart showing sentiment distribution  
- Word clouds for each topic

## Applications

- Understand customer feedback  
- Identify recurring themes in reviews  
- Inform product or service improvements
