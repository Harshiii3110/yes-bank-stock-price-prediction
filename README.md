<h1 align="center">Yes Bank Stock Price Prediction using Machine Learning</h1>

<p align="center">
End-to-end Machine Learning project focused on analyzing and predicting Yes Bank Closing Stock Prices using Exploratory Data Analysis, Statistical Hypothesis Testing, Feature Engineering, and Regression Models.
</p>

---

# Project Overview

This project focuses on predicting the Closing Stock Price of Yes Bank using Machine Learning techniques.

The project follows a complete Machine Learning workflow including:

- Data Understanding
- Data Cleaning
- Exploratory Data Analysis
- Hypothesis Testing
- Data Preprocessing
- Feature Engineering
- Model Building
- Model Evaluation
- Hyperparameter Tuning
- Model Explainability
- Model Saving and Deployment Preparation

The project was implemented using Python in Google Colab.

---

# Problem Statement

Stock prices fluctuate continuously due to multiple market factors. Predicting stock prices accurately can help investors and analysts make better financial decisions and reduce investment risks.

The objective of this project is to build Machine Learning models capable of predicting Yes Bank Closing Stock Prices using historical stock market data.

---

# Dataset Information

The dataset contains historical stock price information of Yes Bank.

## Features Used

| Feature | Description |
|---------|-------------|
| Date | Trading Date |
| Open | Opening Stock Price |
| High | Highest Stock Price |
| Low | Lowest Stock Price |
| Close | Closing Stock Price |

---

# Machine Learning Workflow

```text
Data Collection
       ↓
Data Understanding
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Hypothesis Testing
       ↓
Feature Manipulation
       ↓
Feature Selection
       ↓
Data Transformation
       ↓
Data Scaling
       ↓
Data Splitting
       ↓
Model Implementation
       ↓
Cross Validation
       ↓
Hyperparameter Tuning
       ↓
Model Evaluation
       ↓
Feature Importance Analysis
       ↓
Model Saving
       ↓
Deployment Readiness Check
```

---

# Exploratory Data Analysis

Detailed Exploratory Data Analysis was performed to understand stock price trends and relationships between variables.

## EDA Performed

- Missing Value Analysis
- Correlation Analysis
- Distribution Analysis
- Trend Analysis
- Relationship Visualization
- Outlier Analysis

More than 15 visualizations were created to derive meaningful insights from the dataset.

---

# Hypothesis Testing

Three statistical hypothesis tests were performed to validate relationships between stock market variables.

The tests helped analyze:
- Correlation between Open and Close prices
- Relationship between High and Close prices
- Relationship between Low and Close prices

Statistical significance was evaluated using:
- Correlation Coefficient
- P-value analysis

---

# Data Preprocessing

The following preprocessing steps were applied:

## Missing Value Handling
- Checked for missing values
- Verified dataset completeness

## Feature Manipulation
- Removed unnecessary correlations
- Selected important variables

## Data Transformation
- Numerical feature transformation

## Data Scaling
- StandardScaler was used for feature scaling

## Data Splitting
Dataset was divided into:
- 80% Training Data
- 20% Testing Data

---

# Machine Learning Models

Three Machine Learning Regression models were implemented.

## 1. Linear Regression
Baseline regression model used for stock price prediction.

## 2. Decision Tree Regressor
Used for capturing non-linear relationships between variables.

## 3. Random Forest Regressor
Ensemble learning model used for improving prediction performance.

---

# Hyperparameter Tuning

Hyperparameter optimization was performed using:

## GridSearchCV

Parameters optimized included:
- max_depth
- min_samples_split
- n_estimators

Cross-validation was also applied to evaluate model stability and generalization capability.

---

# Evaluation Metrics

The models were evaluated using:

| Metric | Purpose |
|--------|----------|
| MAE | Measures average prediction error |
| MSE | Measures squared prediction error |
| RMSE | Measures prediction deviation |
| R2 Score | Measures model prediction capability |

---

# Best Performing Model

## Linear Regression

Linear Regression achieved the best performance among all implemented models.

### Performance Highlights

- Highest R2 Score
- Lowest prediction errors
- Strong cross-validation performance
- Better generalization capability

The model successfully predicted Yes Bank Closing Stock Prices with high accuracy.

---

# Feature Importance and Model Explainability

Feature importance analysis was performed using Linear Regression coefficients.

## Key Findings

- Low stock price had the highest influence on Closing price prediction
- High stock price showed strong positive influence
- Open stock price also contributed significantly

This analysis improved understanding of stock market behavior and model interpretability.

---

# Model Deployment Preparation

The best performing model was saved using:

- Pickle (.pkl)
- Joblib

The saved model was successfully:
- Reloaded
- Tested on unseen sample data
- Verified for deployment readiness

---

# Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Computation |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |
| Google Colab | Development Environment |

---

# Future Work

Future improvements can include:

- Deep Learning models such as LSTM
- Real-time stock price prediction
- Financial news sentiment analysis
- Time-series forecasting techniques
- Deployment as a web application

---

# Conclusion

This project successfully demonstrated the implementation of Machine Learning techniques for predicting Yes Bank Closing Stock Prices.

The project covered the complete Machine Learning lifecycle including:
- Data preprocessing
- Exploratory Data Analysis
- Hypothesis Testing
- Model Building
- Hyperparameter Tuning
- Model Explainability
- Model Deployment Preparation

Among all models, Linear Regression performed best and achieved highly accurate stock price prediction results.

The project demonstrates practical application of Machine Learning in the financial domain and provides valuable insights into stock market prediction.

---

# Author

Chunduri Harshitha  
B.Tech CSE (Artificial Intelligence and Machine Learning)  
GITAM University
