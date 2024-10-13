# Sentiment Analysis of Sephora Product Reviews

## Project Overview
This project performs sentiment analysis on product reviews from Sephora, categorizing the reviews into three sentiment classes: Negative, Neutral, and Positive. The analysis employs various natural language processing (NLP) techniques, including text cleaning, feature extraction, and machine learning algorithms, to predict sentiments based on user reviews.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Results](#results)
- [Future Improvements](#future-improvements)

## Technologies Used
- Python
- Pandas
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
The dataset used in this project consists of product reviews from Sephora. The dataset includes the following columns:
- `review`: The text of the product review.
- `rating`: The rating given by the user (1-5).

The dataset can be found on kaggle:
https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews

The python file is included in the main. Outputs are included in separate files.

## Results
Logistic Regression Accuracy: 0.88 or 88%
Naive Bayes Accuracy: 0.84 or 84%

## Future Improvements
Data Augmentation: Increase the number of Neutral sentiment samples for better model learning.
Advanced Algorithms: Experiment with more complex models (e.g., XGBoost, neural networks).
Hyperparameter Tuning: Optimize model parameters for better overall performance.
Enhanced Feature Engineering: Consider using embeddings (Word2Vec, BERT) for improved text representation.
