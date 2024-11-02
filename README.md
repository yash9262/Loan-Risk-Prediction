# Loan-Risk-Prediction

This project classifies loan applicants as likely to default or not based on their financial and credit history data. It employs both traditional machine learning models and deep learning techniques to analyze the data and predict loan risk.

## Table of Contents

- [Features](#features)
- [Data Structure](#data-structure)
- [Getting Started](#getting-started)
- [Model Evaluation](#model-evaluation)
- [Predictions](#predictions)
- [Technologies Used](#technologies-used)

## Features

- Data preprocessing and cleaning.
- Visualization of data using heatmaps, histograms, and boxplots.
- Implementation of machine learning models (Logistic Regression).
- Deep learning model using LSTM for improved accuracy.
- Prediction on new applicant data.

## Data Structure

The dataset should contain the following relevant columns:

- **Duration**: Duration of the loan in months.
- **Credit amount**: Total credit amount.
- **Purpose**: Purpose of the loan (encoded).
- **Saving accounts**: Status of savings accounts (encoded).
- **Sex**: Gender of the applicant (encoded).
- **Risk**: Target variable indicating whether a loan is classified as "good" (1) or "bad" (2).

### Sample New Data for Predictions

```python
new_data = {
    'Duration': [15, 30, 45],
    'Credit amount': [2000, 5000, 8000],
    'Purpose': ['3', '0', '1'],
    'Saving accounts': ['1', '2', '3'],
    'Sex': ['1', '2', '1']
}

