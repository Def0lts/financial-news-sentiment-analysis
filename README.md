# financial-news-sentiment-analysis
Financial news sentiment classification using machine learning

# Financial News Sentiment Analysis

**Machine Learning Capstone Project — Samsung Innovation Campus (2026)**

## Overview

This project classifies financial news headlines into three sentiment categories: Positive, Negative, and Neutral.

The project was developed as an individual capstone project during the Samsung Innovation Campus Artificial Intelligence course.

## Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- TF-IDF
- Logistic Regression
- LinearSVC
- Gradio

## Workflow

1. Data cleaning and exploratory data analysis.
2. Text preprocessing and feature extraction using TF-IDF.
3. Training and comparison of machine learning models.
4. Evaluation using Accuracy, Precision, Recall and Macro F1-score.
5. Creation of a simple prediction interface using Gradio.

## Results

The selected final model was LinearSVC, achieving a Macro F1-score of approximately **0.702** on the evaluation dataset.

## Running the project

1. Install the required Python libraries.
2. Place the dataset `financial_news.csv` in the project directory.
3. Open `financial_news_sentiment.ipynb`.
4. Execute the notebook cells in order.
5. Run the Gradio interface cell to test sentiment predictions.

## Project status

Completed as an individual educational project in June 2026.
