# Fraud Credit Card Transaction Classification

Download Dataset from [kaggle-fraud-transaction-classification](https://www.kaggle.com/rahulgaikwad2010/fraud-transaction-classification) 

In the project, we will be working on machine learning project on credit card fraud

<br/>

## Table Of Contents
-  [Project Structure Overview](#project-structure-overview)
-  [Project Goal](#project-goal)
-  [Data Set](#data-set)
-  [Version](#version)
-  [Author](#author)

<br/>

### Project Structure Overview
```
├── Fraud Credit Card Transaction Classification
|  ├── data          - this folder contains training & testing data.
|  |    └──  transactions.csv (Ommited)
|  │
└────── Fraud Transaction Classification.ipynb
```

<br/>

### Project Goal

The following steps are followed:
- Describe the structure of the date `(statistical summary: number of records, counting max, min, null,...)`
- Plotting histogram of `transactionAmount` column.
- We have duplicated transactions in the dataset - two types: `reversed transaction and multi-swipe`. You need to answer these questions:
  - Identify those types of duplicates
  - Estimate of the total number of transactions and total dollar amount

How do you estimate for the reversed transactions and multi-swipe transactions? 
- The first transaction to be `normal` and exclude it from the number of transaction and dollar amount count

- Modeling - Provide modeling algorithms and say why you use those methods? Why used those features?
  - There is a type of transactions in the dataset has a field called `isFraud`. Build a predictive model to determine whether a given transaction 
will be fraudulent or not.
  - Use an estimate of performance using an appropriate sample

<br/>

## Version

1.0.0 

<br/>

## Author

* **Rahul Gaikwad** - Initial work and development

<br/>

I welcome your questions. Write to rahul.gaikwad2010@gmail.com

<br/>
