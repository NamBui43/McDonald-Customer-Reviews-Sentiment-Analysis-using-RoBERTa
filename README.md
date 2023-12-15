# McDonald-Reviews-Sentiment-Analysis-with-RoBERTa

## Introduction
In this project, I perform a comprehensive analysis on McDonald's Customer Reviews, utilizing a sentiment analysis technique and 2 machine learning algorithms. My goal is to gain valuable insights into customer perceptions of McDonald's services and classify customer sentiment towards McDonald's services based on their their reviews. 

## Data Description
The dataset used in this project contains 33,396 anonymized reviews of McDonald's stores in the United States, obtained from Kaggle (link: https://www.kaggle.com/datasets/nelgiriyewithana/mcdonalds-store-reviews). It includes comprehensive geographic information such as store names, categories, addresses, geographic coordinates, as well as insights into each customer's review, such as review ratings, review texts, and timestamps.

## Sentiment Analysis & Modelling
### Sentiment Analysis
RoBERTa Pretrained Model is used for this project. 

RoBERTa is a transformers model pretrained on a large corpus of English data in a self-supervised fashion
Unlike ntlk model, which only accounts for the meaning of the word itself, this transformer models account for both the meaning of the word itself and the meaning of the word considering the context it is being used in, which is a very important part of human language.

### Modelling
The performances of 2 models - Decision Tree Classifier and Support Vector Classifier are compared. 

## Requirments
The code for this project was written in Python 3.8 and requires the following libraries:
- Pandas
- Numpy
- Sklearn
- Matplotlib
- Seaborn
- transformers
- scipy

## Usage
To run the project, clone the repository and run the Jupyter Notebook file.
