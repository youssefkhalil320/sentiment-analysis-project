# Sentiment Analysis Project

## Project Overview

This project explores various natural language processing (NLP) models for sentiment analysis. We evaluate and compare the performance of several models, including BERT, LSTM, Multinomial Naive Bayes, and Logistic Regression. The primary goal is to understand the trade-offs between model performance and computational efficiency.

### Key Models

- **BERT**: Achieved a Matthews Correlation Coefficient (MCC) of 0.73 and an evaluation loss of 0.52, with a model size of 0.6 GB.
- **LSTM**: Achieved a test accuracy of 82% with a compact model size of 0.02 GB.
- **Multinomial Naive Bayes**: Achieved a test accuracy of 0.53 with a model size of 0.1 GB.
- **Logistic Regression**: Achieved a test accuracy of 0.82 with a model size of 0.05 GB.

## Setup

To run this project, follow these instructions:

### Prerequisites

Make sure you have the following packages installed:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `tensorflow`
- `keras`

You can install these packages using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras
