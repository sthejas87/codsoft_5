# Credit Card Fraud Detection

Build a machine learning model to identify fraudulent credit card transactions.

## Installation

Install the required libraries:

```bash
pip install pandas scikit-learn imbalanced-learn seaborn
```

## Usage

Clone the repository.

Download the dataset (creditcard.csv) from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and place it in the repository directory.

Run the script.

## Results

The script preprocesses and normalizes the transaction data, handles class imbalance using SMOTE (Synthetic Minority Over-sampling Technique), and trains a Random Forest Classifier. Performance metrics including precision, recall, and F1-score are evaluated and printed for both the original imbalanced dataset and the balanced dataset after SMOTE.
