# Loan-Rate-Prediction

Outline of Work:

1. Data Cleaning & Feature Engineering
2. Data Visualization
3. Model Building & Selection
4. Model Testing on Holdout Set
5. Future techniques


Data Cleaning & Feature Engineering:

I will engineering my features through the following techniques:
- one-hot encoding
- get_dummies
- cat.codes
- .str.replace & .str[4:]
- tdidf, Truncated SVD and KMeans
- imputing with cluster's mean values
- function building

Model Building:

I have tested the following models:
- Decision Tree Regressor
- Random Forrest
- Gradient Boost
- Ridge

I ultimately selected Gradient Boost as my final model based on it having the lowest relative RMSE result
