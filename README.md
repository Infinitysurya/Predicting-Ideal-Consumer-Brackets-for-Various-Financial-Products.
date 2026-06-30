# Predicting Ideal Consumer Brackets for Various Financial Products

## Project Overview
The primary objective of this project is to predict the probability of consumers purchasing specific financial products, such as Mutual Funds, Credit Cards, and Consumer Loans. These predictions are derived by analyzing historical consumer account information and transaction details.

## Data Collection and Preprocessing
* **Source Material:** The foundational dataset was sourced from Kaggle.
* **Exploratory Data Analysis (EDA):** Conducted thorough EDA to identify underlying patterns and trends within the consumer data.
* **Data Cleaning:** Streamlined the dataset by removing redundant columns and appropriately imputing missing values using statistically robust measures.

## Data Simulation (Agent-Based Modeling)
To address challenges related to data scarcity and insufficient sample sizes, Agent-Based Modeling (ABM) was utilized. This technique allowed for the generation of synthetic data that accurately mirrored the distributions and statistical properties of the original dataset, providing a more robust foundation for model training.

## Modeling and Results
Multiple machine learning algorithms were trained and evaluated to find the most effective predictive model for this dataset. 

* **Models Tested:** Included XGBoost, Logistic Regression, and other baseline classifiers.
* **Conclusion:** Logistic Regression ultimately emerged as the best-performing model for this specific classification task, consistently outperforming the alternatives across key evaluation metrics, including overall Accuracy and F1-score.
