# Bank_data
# Evaluation of Credit Risk Based on Direct Marketing Campaigns

This project involves developing a machine learning model to evaluate credit risk using data from direct marketing campaigns of a Portuguese banking institution. The campaigns were based on phone calls, and the goal is to predict whether a customer will subscribe to a financial product (yes: 1, no: 0) by comparing logistic regression models.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Data Extraction and Preprocessing](#data-extraction-and-preprocessing)
- [Modeling](#modeling)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [How to Run](#how-to-run)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
In this project, we built a logistic regression model to estimate the probability of a customer subscribing to a financial product based on various factors such as income, debt level, and employment status. The project focuses on evaluating credit risk and helps in making informed decisions about offering financial products to customers.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Logistic Regression

## Data Extraction and Preprocessing
We started by extracting and analyzing the data from the marketing campaigns. The data was cleaned and preprocessed using a pipeline to ensure high quality and relevance for modeling.

Key steps:
- Handling missing data
- Encoding categorical variables
- Feature scaling

## Modeling
The project utilized logistic regression as the primary model to predict the binary outcome (1: subscribed, 0: not subscribed). The model was trained and tested on the processed dataset.

## Evaluation Metrics
To assess the model's performance, the following metrics were calculated:
- **Accuracy:** Measures the proportion of correctly classified instances.
- **Sensitivity (Recall):** Measures the proportion of actual positives that are correctly identified.
- **Specificity:** Measures the proportion of actual negatives that are correctly identified.
- **AUC ROC:** Represents the area under the ROC curve, indicating the model's ability to discriminate between classes.

## Results
The logistic regression model provided valuable insights into the factors influencing customer subscriptions. The evaluation metrics demonstrated the model's effectiveness in predicting credit risk.


