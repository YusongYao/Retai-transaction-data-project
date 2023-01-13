# Retai-transaction-data-project

This project uses the retail transactional dataset from Kaggle: https://www.kaggle.com/datasets/regivm/retailtransactiondata?select=Retail_Data_Response.csv

The goal of this project is to first apply feature engineering techniques to generate features that caputure annual and monthly spending patterns repectively, and then apply supervied machine learning models on both annual and monthly spending aggregations to notify the difference in order to see which should be a better aggregation.

In the "Feature Engineering" file, the dataset was loaded and modified into separate excel files that capture different feature, which include annual_features.xlsx that captures annual aggregations, mth_rolling_features.xlsx that contains monthly rolling features, and so on.

Then in the "Supervised Learning" file, files created previously were aggregated into retail response data with monthly feature outputs and annually feature outputs, the data was preprocessed and splitted into train and test sets, different supervised classification model: Logistic regression, Decision tree, Random forest were applied to compare the performence.
