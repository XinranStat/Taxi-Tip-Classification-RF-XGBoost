# **Taxi Tip Generosity Classification Project**

## **Project Overview**
This project predicts whether a taxi customer will tip generously (≥ 20% of the fare) using machine learning models. The classification models used include **Random Forest** and **XGBoost**.  

The goal is to develop an accurate prediction model to help taxi services better understand tipping behaviors. The project evaluates model performance using **accuracy, precision, recall, F1-score, and AUC**.

## **Dataset**
- The dataset contains ride-related information, including fare amount, trip duration, distance, passenger count, and more.
- The target variable is **binary (0 or 1)**:
  - **1** → Generous tip (≥ 20% of the fare)
  - **0** → Not generous (< 20% of the fare)

## **Workflow**
1. **Data Cleaning & Preprocessing**
2. **Exploratory Data Analysis (EDA)**
   - Understanding distributions of fare, tip percentage, and categorical variables.
   - Feature importance analysis.
   
*(Note: A more detailed multi-linear regression analysis is available in a separate project.)*

3. **Machine Learning Models**
   - **Random Forest**
   - **XGBoost**

4. **Model Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-score, and AUC.
   - Confusion matrix analysis to understand misclassifications.

## **How to Run the Notebook**
1. Install required libraries:  
   ```bash
   pip install pandas numpy scikit-learn xgboost seaborn matplotlib
