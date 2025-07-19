# Sentiment-Analysis
## Overview
#### This project performs sentiment analysis to classify text reviews into positive or negative categories. The pipeline includes text preprocessing, training different deep learning models.

## My Project

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1j7JNAwir8-G-O_mee8Tmetnnk2jVuXU0#scrollTo=_ByaomWloRKn)


## Steps Performed

### 1. Data Exploration
- Analyzed the distribution of positive and negative reviews.

### 2. Text Preprocessing
- Cleaned text by removing punctuation, numbers, and special characters.
- Tokenized sentences into words.
- Removed stop words and performed lemmatization.
- Converted words to sequences using **Keras Tokenizer**.
- Padded sequences to a fixed length for uniformity.

### 3. Model Training
- Built and trained multiple deep learning models including:
  - `SimpleRNN`
  - `GRU`
  - `LSTM`
  - `Bidirectional LSTM`
  - `CNN + LSTM`
- Tuned various hyperparameters:
  - Embedding dimensions
  - Number of units
  - Dropout rate
  - Learning rate, batch size, etc.

### 4. Model Evaluation
- Evaluated model performance using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion matrix


