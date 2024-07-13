# credit-card-fraud-detection

V1-V28 (PCA Components):
  - These features are obtained through PCA, which is a dimensionality reduction technique.
  - For privacy reasons, the original features (such as transaction amount, location, and time) have been transformed into these principal components.
  - Each of these components captures different aspects of the transaction data.
  - While we don’t know the exact meaning of each V1-V28 individually, collectively, they summarize the variation in the original features.
Amount:
  - The Amount feature represents the transaction amount associated with each credit card transaction.
Class:
  - The Class feature is the target variable. It indicates whether a transaction is fraudulent (labeled as 1) or legitimate (labeled as 0).

The dataset is available on kaggle.com (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download)
The original dataset is very unbalanced for model training (284315 - legit transactions , 492 fraudulent transactions), so we have to first convert the dataset to a balanced one.
