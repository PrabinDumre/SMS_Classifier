# SMS Spam Detection using Python

## Overview

This repository contains the code for building a robust SMS spam detection model using Python and scikit-learn. The implementation includes data preprocessing, feature extraction, Naive Bayes classification, and model evaluation.

## Dataset

The model was trained on the Kaggle SMS Spam Collection Dataset, which includes labeled SMS messages as spam or non-spam. The dataset was loaded and preprocessed using pandas, and challenges like UnicodeDecodeError were addressed by specifying the 'latin1' encoding.

## Tools and Libraries

- Python
- pandas
- scikit-learn
- Jupyter Notebook

## Code Highlights

1. **Data Preprocessing:** Cleaned and prepared the dataset for model training.
2. **Feature Extraction:** Utilized the bag-of-words model with CountVectorizer for text representation.
3. **Classification Model:** Implemented a Naive Bayes classifier for spam detection.
4. **Model Evaluation:** Assessed the model's performance using accuracy, confusion matrix, and classification report.

## Learnings

- Successfully handled UnicodeDecodeError by adjusting the encoding.
- Explored different techniques for SMS spam detection using scikit-learn.
- Customized the code to adapt to the structure of the Kaggle dataset.

