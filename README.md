# Findings Summary: Classifier Performance Comparison - Predict If Bank Clients Will Subscribe To A Deposit During A Marketing Campaign

## Author
- Shaurya Srivastava

## Data Analysis Notebook
- [Link to Jupyter Notebook](comparing_classifiers.ipynb)

## Overview
This project aimed to build Logistic Regression, KNN, Decision Tree, and SVM classifiers that the bank can use to predict whether the client subscribes to the deposit offered during the campaign based on certain factors. The goal was to compare the performance of the different classifiers and pick the best one that the bank should use.

The chosen models for evaluation was the Decision Tree classifier trained using Grid Search on the Precision Metric. After thorough comparison of Logistic Regression, KNN, Decision Tree, and SVM classifiers trained using Grid Search (and Halving Grid Search) on the Accuracy and Precision Metric, the Decision Tree classifier trained using Grid Search on the Precision Metric was identified as the best model with 89% accuracy and 70% Precision.

## Business Success Criteria
The project successfully met the business criteria, providing a classifier that accurately predicts whether the client subscribes to the deposit offered during the campaign based on certain factors. The project also identifies the key features that influence the customer's response. 

## Model Selection
- **Selected Model:** Decision Tree classifier trained using Grid Search on the Precision Metric
  - Accuracy: 89%
  - Precision: 70%
  - Fit Time: 26 secs

## Project Steps
1. **Data Cleaning:** The data cleaning process effectively preserved a substantial portion of the dataset for modeling.
2. **Exploratory Data Analysis (EDA):** Explored key features and their impact on whether customers subscribed during the marketing campaign.
3. **Model Building:** Developed Logistic Regression, KNN, Decision Tree, and SVM classifiers.
4. **Evaluation:** Evaluated models based on accuracy and precision, leading to the selection of the Decision Tree classifier trained using Grid Search on the Precision Metric.

## Project Outcomes
- **Learnings:** Acquired knowledge in building classifiers, comparing the performances of different classifiers, and selecting the best classifier model.
- **Business Insights:** Identified crucial factors influencing customer responses for subscribing to a deposit during a bank's marketing campaign.

## Areas for Improvement
1. **Model Refinement:** Experiment with model parameters for enhanced accuracy.
2. **Hardware Upgrade:** Due to hardware limitations, explore options like better GPUs or cloud computing for testing more complex models. This is especially important for when using SVM with Grid Search, as it takes a lot of time. 

## Conclusion
The project successfully addressed the business goals, providing the bank with an accurate and precise classifier to determine if a customer would subscribe to a deposit during a marketing campaign. The bank should specifically target customers they haven't contacted in many days, especially customers never contacted, in the month of October with a telephone. They should contact customers when the bank has a large number of employees and a large euribor 3 month rate. 

Future improvements include refining the model and exploring advanced computing resources for more sophisticated analyses. 