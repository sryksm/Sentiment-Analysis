# Project Title: Sentiment Analysis on Indonesia President Election 2019 Tweets

## Overview
This project aims to perform sentiment analysis on tweets related to the Indonesia President Election in 2019. The primary goal is to classify tweets into three sentiment categories: positive, negative, and neutral. Two different models, Random Forest (RF) and Long Short-Term Memory (LSTM), are employed for classification.

![download](https://github.com/sryksm/Sentiment-Analysis---IndoAI/assets/109900273/842add8e-a7df-4b57-a831-9269008ec7e5)

## Workflow
A brief step-by-step on what i've done:
1. Import libraries and load dataset (you can check on Datasets/tweets.csv)
2. Data understanding and EDA
   Exploratory Data Analysis (EDA) is conducted to gain insights into the dataset. This step involves exploring the distribution of sentiments and identifying potential patterns or trends.
3. Data Preprocessing
   The tweets undergo extensive preprocessing to ensure the quality and standardization of the text data. Steps include punctuation removal, stopword removal, standardization of words to meet the KBBI standard, slang removal, lemmatization, stemming, and tokenization.
4. TF-IDF Vectorization and RF model
   TF-IDF is employed as the vectorizer to convert the preprocessed text data into numerical features. The Random Forest (RF) classifier is trained using these features.
5. Keras Tokenizer and LSTM
   The Keras Tokenizer is utilized to tokenize the text data, and an Embedding layer is used to process word embeddings. The LSTM model is constructed and trained.
6. Model Evaluation
   - For RF:
     
   ![image](https://github.com/sryksm/Sentiment-Analysis---IndoAI/assets/109900273/6d2c2ec8-de6e-4e60-bb78-f4d0762d0b15)

   - For LSTM:
   
   ![image](https://github.com/sryksm/Sentiment-Analysis---IndoAI/assets/109900273/a94091d1-7e18-49aa-94a4-a3c38548c133)


## Conclusion
RF model and LSTM on my scenario are ending in the same performance level. For further evals might be better to go more on LSTM layer modifications

Contact me on: suryakusumasae@gmail.com


