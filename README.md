# bluebook-bulldozer-price-regression

## Predicting the Sale Price of Bulldozers Using Machine Learning
This project demonstrates an end-to-end machine learning workflow to predict the future sale price of bulldozers based on their characteristics and historical data. The dataset is sourced from the Kaggle Bluebook for Bulldozers competition: https://www.kaggle.com/c/bluebook-for-bulldozers/data

### 1. Problem Definition
How well can we predict the future sale price of a bulldozer given its characteristics and past sales data?

### 2. Data
The dataset consists of three main files:

Train.csv: Data through the end of 2011 (used for training the model).
Valid.csv: Data from January 1, 2012 - April 30, 2012 (used for validation and leaderboard scoring).
Test.csv: Data from May 1, 2012 - November 2012 (used for final ranking, released later in the competition).
For more details, visit the competition data page: https://www.kaggle.com/c/bluebook-for-bulldozers/data

### 3. Evaluation
The performance metric for this project is Root Mean Squared Log Error (RMSLE). The objective is to minimize the RMSLE between actual and predicted sale prices.

More information can be found in the competition evaluation section: https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation

### 4. Features
A detailed dictionary of the dataset features is available here: https://docs.google.com/spreadsheets/d/18ly-bLR8sbDJLITkWG7ozKm8l3RyieQ2Fpgix-beSYI/edit?gid=1021421956#gid=1021421956

### 5. Modeling
This project involves exploratory data analysis (EDA) and the implementation of regression models to predict bulldozer sale prices, with a focus on minimizing RMSLE.
