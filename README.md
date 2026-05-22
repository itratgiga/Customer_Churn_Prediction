# Customer Churn Prediction & Risk Segmentation Dashboard

## Overview

This project focuses on predicting customer churn for a telecom company using Machine Learning techniques. The goal is to identify customers who are likely to leave the service and segment them into different risk categories so businesses can take proactive retention actions.

The project includes:

* Exploratory Data Analysis (EDA)
* Data preprocessing and feature engineering
* Machine Learning model training and evaluation
* Customer risk segmentation
* Data visualization and business insights

---

## Dataset

Dataset Used: Telco Customer Churn Dataset

Source: Kaggle

The dataset contains customer demographic information, subscription details, billing information, tenure, and churn status.

Rows: 7,043
Columns: 21+

Target Variable:

* `Churn`

  * Yes = Customer left
  * No = Customer stayed

---

## Technologies Used

* Python 3
* Pandas
* NumPy
* Scikit-learn
* XGBoost / Gradient Boosting
* Matplotlib
* Seaborn
* Plotly
* Jupyter Notebook

---

## Project Workflow

### 1. Data Loading & Exploration

* Loaded and inspected the dataset
* Checked missing values and data types
* Performed statistical analysis
* Created correlation heatmaps

### 2. Data Preprocessing

* Converted `TotalCharges` to numeric
* Encoded categorical variables
* Scaled numerical features
* Performed train-test split

### 3. Feature Engineering

Created additional features such as:

* ChargesPerMonth
* SeniorWithNoSupport

### 4. Model Training

Trained and compared:

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier

### 5. Model Evaluation

Evaluated models using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix
* ROC Curve

### 6. Risk Segmentation

Customers were segmented into:

* High Risk
* Medium Risk
* Low Risk

based on churn probability scores.

### 7. Data Visualization

Generated multiple visualizations including:

* Feature Importance Chart
* Churn by Contract Type
* Tenure Distribution
* Risk Tier Pie Chart
* Correlation Heatmap

---

## Best Performing Model

Gradient Boosting achieved the best overall performance with the highest ROC-AUC score and balanced classification metrics.

---

## Key Insights

* Customers with month-to-month contracts had higher churn rates.
* Customers with lower tenure were more likely to churn.
* High monthly charges increased churn probability.
* Long-term contracts reduced churn risk significantly.

---

## Business Recommendations

* Provide loyalty discounts to high-risk customers.
* Encourage users to switch to yearly contracts.
* Improve technical support services.
* Monitor new customers during the initial months.

---

## Future Improvements

* Add real-time prediction dashboard using Streamlit
* Use deep learning models for better accuracy
* Integrate customer support interaction data
* Deploy model using Flask or FastAPI

---

## Author

Itrat zehra Giga

Internship Project — Customer Churn Prediction & Risk Segmentation Dashboard
