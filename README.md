# Fake News Detection Using Machine Learning

## Overview
This project aims to build a **Fake News Detection System** using multiple machine learning algorithms to classify news articles as either **real** or **fake**. The system uses four popular classification algorithms:
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **Gradient Boosting**

The model is trained on a labeled dataset of news articles and uses various natural language processing (NLP) techniques to process the text data.

## Algorithms Used
1. **Logistic Regression**: A simple but effective algorithm for binary classification tasks.
2. **Decision Tree**: A non-linear algorithm that splits the data into subsets based on feature values to make predictions.
3. **Random Forest**: An ensemble method that creates multiple decision trees and aggregates their predictions.
4. **Gradient Boosting**: A boosting technique that builds models sequentially, each model correcting the errors of the previous one.

## Project Setup

### Requirements
- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`
  - `nltk`
  - `xgboost`
  - `joblib` (for model saving)

Install the required libraries by running:
```bash
pip install -r requirements.txt
