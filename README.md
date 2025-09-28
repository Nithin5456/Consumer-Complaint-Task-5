# Consumer Complaint Classification
## Overview
This project builds a text classification model to automatically categorize consumer complaints into one of the following categories:

o Credit Reporting
o	Debt Collection
o	Consumer Loan
o	Mortgage
It uses TF-IDF features from complaint narratives and applies machine learning models such as Logistic Regression and Naive Bayes. The pipeline also handles class imbalance using oversampling.

## Features
### •	Text preprocessing:
o	Lowercasing
o	Removing punctuation and non-alphabetic characters
o	Stopword removal
o	Lemmatization
### •	Feature engineering:
o	TF-IDF vectorization
### •	Handling imbalanced classes:
o	Oversampling using RandomOverSampler
### •	Models used:
o	Logistic Regression 
o	Multinomial Naive Bayes
### •	Evaluation metrics:
o	Accuracy
o	Macro F1-score
o	Classification report (precision, recall, F1)

