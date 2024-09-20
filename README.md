# Credit Risk Analysis

This project uses feature selection techniques like Correlation matrix, p-value backward elimination 
to remove unuseful features and then train ML models on the processed data.

Dataset: Kaggle Lending club Dataset (https://www.kaggle.com/datasets/ethon0426/lending-club-20072020q1/data)

## About Data: 
LendingClub is an American peer-to-peer lending company, headquartered in San Francisco, California.
It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), 
and to offer loan trading on a secondary market.

LCDataDictionary.xlsx has the description of the features in the dataset.

## Training and Testing split
Training data : Lending club data from 2007-2015.

Testing data : Lending club data from 2016

Test to train ratio: 27.6%

## Results

Logistic regression and Random forest classifier were hypertuned with 3-fold cross validation
and performance analysed on testing data.

### Metrics for logistic regression
!["Table logistic regression"](<plots/table_lr.png>)

### Plots for logistic regression
!["Model performance using Logistic regression"](<plots/feature_importance_lg.png>)
!["Precision recall logistic regression"](<plots/precision_recall_lr.png>)


