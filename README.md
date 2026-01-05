# fake-review-analysis
MSc Data Science project: sentiment classification of Amazon and Flipkart reviews using LR, SVM and Naive Bayes
# Fake Review Sentiment Classification (MSc Project)

This repository contains the code for my MSc Data Science project.

The project analyses Amazon and Flipkart product reviews using
Natural Language Processing (NLP) and Machine Learning models
(Logistic Regression, Linear SVM and Naive Bayes).

## Contents

- `notebooks/` or main `.ipynb` file – full analysis pipeline
- `data/` – (optional) small sample of review data or data description
- `README.md` – this file

## Main steps

1. Load Amazon and Flipkart review datasets (from Kaggle).
2. Clean and pre-process review text.
3. Convert text to numerical features using TF-IDF (1–2 grams, 5000 features).
4. Train Logistic Regression, Linear SVM and Naive Bayes models.
5. Evaluate models using accuracy and classification reports.
6. Analyse confusion matrix and discuss limitations.

## How to run

1. Create a Python environment (e.g. using Anaconda).
2. Install required libraries: `pandas`, `numpy`, `scikit-learn`, `nltk`, `matplotlib`, `seaborn`.
3. Open the notebook and run the cells in order.

This work was completed as part of the MSc Data Science Final Project.
