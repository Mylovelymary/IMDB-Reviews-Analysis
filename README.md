# IMDB Reviews Analysis

This project analyzes movie reviews from the IMDB dataset using NLP techniques. The goal is to classify reviews as positive or negative and visualize key insights.

## Project Overview
- **Data**: IMDB Reviews dataset (from `tensorflow_datasets`).
- **Steps**:
  1. Cleaned text data (removed stop words, tokenized using NLTK).
  2. Visualized frequent words with word clouds for positive and negative reviews.
  3. Plotted a histogram of review lengths.
  4. Classified reviews using Logistic Regression (TF-IDF vectorization).
- **Results**:
  - Accuracy: 0.88
  - Precision, Recall, F1-Score: ~0.88 for both classes.

## Visualizations
### Word Cloud for Positive Reviews
### Word Cloud for Negative Reviews
### Review Length Distribution

Dependencies:
- Python 3.11
- tensorflow_datasets
- pandas
- nltk
- wordcloud
- matplotlib
- plotly
- scikit-learn
