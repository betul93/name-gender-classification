# name-gender-classification
Gender Prediction from Names: Naive Bayes vs. Decision Tree Comparison

This project uses machine learning models (Naive Bayes and Decision Tree) to predict gender (male/female) based on names. The model learns from simple name features like last letter and name length.

📌 Project Overview
Dataset: name_gender_dataset.csv (Contains "Name" and "Gender" columns).

Models Used:

Gaussian Naive Bayes

Decision Tree Classifier

Features:

last_letter: Last character of the name (e.g., "Emma" → "a").

name_length: Length of the name (e.g., "James" → 5).

Performance Metric: Accuracy

🚀 How to Run
1. Prerequisites
Python 3.x

Google Colab or Jupyter Notebook

Libraries:
pandas, scikit-learn

🔍 Technical Details
Feature Engineering
last_letter: Extracted using name[-1].lower().

name_length: Calculated via len(name).

Model Training
Dataset split: 70% training, 30% testing (random_state=42).

Categorical features encoded using DictVectorizer.
