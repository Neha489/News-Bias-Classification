# News-Bias-Classification

This project classifies political bias in Indian news articles using both machine learning (ML) and transformer-based deep learning (DL) models like BERT and RoBERTa.

## Features

- Text preprocessing (stopwords, stemming)
- ML models: Logistic Regression, SVM, XGBoost
- DL models: BERT, RoBERTa (via Hugging Face)
- SMOTE for class balancing
- Confusion matrix & feature importance visualization
- CSV/JSON support for inputs and outputs

## Dataset

Includes fields like:
- title, text, source
- keywords/biased_words
- bias_category (e.g., Left, Right, Center)
- Optional reasoning

## Usage

bash
# Train ML model
python train_ml_model.py --data_path data/news.csv

# Train BERT model
python train_bert.py --model bert-base-uncased --epochs 3


