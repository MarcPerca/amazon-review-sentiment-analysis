Amazon Review Sentiment Analysis
This project performs sentiment analysis on Amazon Fine Food Reviews using Python, pandas, and machine learning techniques. The goal is to explore the dataset, preprocess the data, and build a text classification model to predict whether a review is positive or negative.

Dataset
The dataset is sourced from Kaggle - Amazon Fine Food Reviews. It contains over 500,000 reviews with features such as review text, score, and user information.

Note: The dataset file Reviews.csv must be downloaded separately due to its size and placed in the same directory as the notebook.

Project Overview
Exploratory Data Analysis (EDA):
Analyze distribution of reviews, scores, and product ratings to understand the dataset characteristics.

Data Preprocessing:
Clean and transform the data, including labeling sentiments based on review scores and preparing the text for modeling.

Sentiment Classification Model:
Use a machine learning pipeline with text vectorization (CountVectorizer) and a Multinomial Naive Bayes classifier to predict sentiment.

Model Evaluation:
Assess model performance using accuracy, precision, recall, and F1-score metrics.

Requirements
Python 3.x

pandas

matplotlib

scikit-learn

You can install the required packages with:

bash
Copiar
Editar
pip install pandas matplotlib scikit-learn
How to Run
Download the Reviews.csv file from the Kaggle dataset and place it in the same folder as the notebook amazon_sentiment.ipynb.

Open the notebook using Jupyter Notebook, JupyterLab, or Google Colab.

Run the cells sequentially to follow the full data analysis, preprocessing, model training, and evaluation.

Results
The trained model achieves approximately 90% accuracy in classifying positive and negative reviews, demonstrating the potential of simple text classification techniques in sentiment analysis.
