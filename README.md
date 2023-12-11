# Credit Card Fraud Detection using Machine Learning in Python #

In this Jupyter notebook, we aim to develop a predictive model to discern whether a credit card transaction is fraudulent or legitimate through the application of Machine Learning techniques.

## Dataset Overview

The dataset comprises credit card transactions made by European cardholders in September 2013. With a total of 284,807 transactions recorded over two days, there are 492 instances of fraud. Notably, the dataset exhibits a significant class imbalance, with fraudulent transactions constituting a mere 0.172% of the total.

For confidentiality reasons, the input features have undergone numerical transformation using Principal Component Analysis (PCA).

## Dataset Source

The dataset is sourced from Kaggle, and you can download it [here](https://www.kaggle.com/mlg-ulb/creditcardfraud).

**Note:** The dataset file is not included in this repository due to its size.

## Getting Started

To replicate and explore the analysis, follow these steps:

1. Download the dataset from the provided [Kaggle link](https://www.kaggle.com/mlg-ulb/creditcardfraud).
2. Save the dataset file in the same directory as this notebook.

## Dependencies

Ensure you have the following Python libraries installed:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

Install any missing libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
