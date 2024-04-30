# Credit Card Fraud Detection

## About the Data

This dataset comprises credit card transactions made by European cardholders in September 2013. It spans transactions over two days, totaling 284,807 transactions, with 492 identified as fraudulent. With frauds accounting for only 0.172% of all transactions, the dataset exhibits high class imbalance.

The dataset primarily consists of numerical input variables resulting from a Principal Component Analysis (PCA) transformation. Features V1 to V28 represent principal components obtained through PCA, while 'Time' and 'Amount' remain untransformed. 'Time' indicates the seconds elapsed between each transaction and the first one, while 'Amount' represents the transaction amount. The response variable, 'Class', is binary, taking the value 1 for fraud and 0 otherwise.

Due to the class imbalance ratio, accuracy is measured using the Area Under the Precision-Recall Curve (AUPRC), as confusion matrix accuracy lacks significance in unbalanced classification scenarios.

[Source](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## Libraries Used

- `import numpy as np`
- `import pandas as pd`
- `import plotly.express as px`
- `import matplotlib.pyplot as plt`
- `import seaborn as sns`
- `import statsmodels.api as sm`
- `from sklearn.metrics import confusion_matrix`
- `from sklearn.preprocessing import binarize`
- `from sklearn.metrics import roc_curve`
- `import warnings`

Make sure to have these libraries installed to run the code successfully.
