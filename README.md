# Natural Language Processing - NLP
This repository sharing my practice different algoritms in Natural Language Processing (NLP) by different dataset.

### Algorithms in NLP:
1. Similarity Search - Facebook AI Similarity Search (Faiss)
2. Classification - Resume Selector with Naive Bayes Classifiers
3. Classification - Stocks Sentiment Analysis with RNN and LSTM
4. Classification - Fake News with RNN and LSTM
5. Text Generation - Generate New Recipes with GPT-2

### Logs:

2022-07-25 Uploaded ***Text Generation - Generate New Recipes with GPT-2 220725.ipynb***

***Executive Summary:***

***Goal***: 
- Finetuning a distilled version of GPT-2 on a smaller-scale dataset comprising recipes
- The recipes are split into ingredients and instructions
- Use GPT-2 to generate instructions from a list of ingredients

***Table of Content:***

0. Data Sample
1. Exploratory Data Analysis and Preprocessing
2. Dataset Preparation
3. GPT-2 Pretrained Model Formulation and Theory

----------------------------------------------------------------------------------------------------------

2022-07-25 Uploaded ***Classification - Fake News with RNN and LSTM 220725.ipynb***

***Executive Summary:***

***Goal:***
- Detect fake news based on Recurrent Neural Networks (RNN) and Long Short Term Memory (LSTM)

***Result:***
- Overall accuracy 1.0 (total number of data 8980)
- f1-score for real news 1.0 (1 of 4684 real news predicted as fake news) and fake news 1.0 (4 of 4296 real news predicted as fake news)

----------------------------------------------------------------------------------------------------------
2022-07-24 Uploaded ***Classification - Stocks Sentiment Analysis with RNN and LSTM 220724.ipynb***

***Executive Summary:***

***Goal:***
- To understand the sentiment from public tweets, which could be used as a factor while making a buy/sell decision of securities based on Recurrent Neural Networks (RNN) and Long Short Term Memory (LSTM)

***Result:***
- Overall accuracy 0.67 (total number of data 5791)
- f1-score for not flagged 0.65 and flagged 0.69 (number of not flagged data 4632  and number of flagged data 1159)

----------------------------------------------------------------------------------------------------------
2022-07-24 Uploaded ***Classification - Resume Selector with Naive Bayes Classifiers 220724.ipynb***

***Executive Summary:***

***Goal:***
- To predict whether a given resume text is flagged or not with Navie Bayes Classifiers

***Result:***
- Overall accuracy 0.72 (total number of data 125)
- f1-score for not flagged 0.81 and flagged 0.46 (number of not flagged data 92 and number of flagged data 33)

----------------------------------------------------------------------------------------------------------
2022-07-24 Uploaded ***Classification - Fake News with RNN and LSTM 220724.ipynb***

***Executive Summary:***

***Goal:***
- Detect fake news based on Recurrent Neural Networks (RNN) and Long Short Term Memory (LSTM)

----------------------------------------------------------------------------------------------------------

2022-07-22 Uploaded ***Similarity Search - Facebook AI  Faiss - Twitter Airline Dataset 220722.ipynb***

***Executive Summary:***

***What is Facebook AI Similarity Search (Faiss)?***

- Faiss is a library developed by Facebook AI — that enables ***efficient similarity search***.

- Given a set of vectors, we can index them using Faiss

- Using another vector (the query vector), we ***search for the most similar vectors within the index***.

Twitter Airline Dataset originally came from: https://appen.com/pre-labeled-datasets/

----------------------------------------------------------------------------------------------------------
