# Customer Churn Analysis

This project aims to analyze customer churn using machine learning techniques. The goal is to predict which customers are most likely to leave a service, providing valuable insights for customer retention strategies. The dataset used for this analysis is the **Telco Customer Churn** dataset, which includes customer demographics, account information, and service usage data.

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Installation](#installation)
4. [Machine Learning Model](#machine-learning-model)
5. [Model Evaluation](#model-evaluation)
6. [Results](#results)
8. [Contributing](#contributing)

---

## Project Overview

Customer churn is a major concern for businesses, as retaining existing customers is more cost-effective than acquiring new ones. This project involves analyzing customer data to identify factors that contribute to churn, using machine learning models to predict which customers are likely to churn, and providing actionable insights.

The analysis involves:
- Data preprocessing and cleaning
- Exploratory data analysis (EDA)
- Model training and hyperparameter tuning
- Evaluation using accuracy and other performance metrics

---

## Dataset Description

The dataset used for this analysis is the **Telco Customer Churn** dataset from Kaggle. The dataset contains the following features:

- **customerID**: Unique identifier for each customer
- **gender**: Gender of the customer (Male/Female)
- **SeniorCitizen**: Whether the customer is a senior citizen (1 = Yes, 0 = No)
- **Partner**: Whether the customer has a partner (Yes/No)
- **Dependents**: Whether the customer has dependents (Yes/No)
- **tenure**: Number of months the customer has been with the company
- **PhoneService**: Whether the customer subscribes to phone service (Yes/No)
- **MultipleLines**: Whether the customer has multiple phone lines (Yes/No)
- **InternetService**: Type of internet service the customer subscribes to (DSL, Fiber optic, No)
- **OnlineSecurity**: Whether the customer has online security as part of their internet service (Yes/No/No internet service)
- **OnlineBackup**: Whether the customer has online backup as part of their internet service (Yes/No/No internet service)
- **DeviceProtection**: Whether the customer has device protection as part of their internet service (Yes/No/No internet service)
- **TechSupport**: Whether the customer has technical support as part of their internet service (Yes/No/No internet service)
- **StreamingTV**: Whether the customer has TV streaming services (Yes/No/No internet service)
- **StreamingMovies**: Whether the customer has movie streaming services (Yes/No/No internet service)
- **Contract**: Type of contract the customer has (Month-to-month, One year, Two year)
- **PaperlessBilling**: Whether the customer has paperless billing (Yes/No)
- **PaymentMethod**: The customer's preferred payment method (Bank transfer, Credit card, Electronic check, Mailed check)
- **MonthlyCharges**: The amount the customer pays per month for services
- **TotalCharges**: The total amount charged to the customer
- **Churn**: Whether the customer churned (Yes/No)

---

## Installation

To run this project locally, follow these steps:

### Prerequisites
- Python 3.7+
- Anaconda or pip for package management

### Step 1: Clone the repository

```bash
git clone https://github.com/bensbehChaimae/Customer-Churn-Analysis.git
cd Customer-Churn-Analysis
```

## Machine Learning Model :

We used the following models for predicting customer churn:
- **Logistic Regression**
- **Random Forest**
-**Support Vector Machine (SVM)**


## Model Evaluation:

After training the models, we evaluated their performance using various metrics:

| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 0.79     | 0.75      | 0.70   | 0.72     |
| Random Forest       | 0.83     | 0.80      | 0.75   | 0.77     |
| SVM                 | 0.77     | 0.74      | 0.72   | 0.73     |

Based on these results, the **Random Forest** model performed the best in terms of overall accuracy and other metrics.

## Results :

After training the model, we were able to predict customer churn with reasonable accuracy. This model can now be used for customer retention strategies in the business.

## Contributing :

We welcome contributions to improve the analysis, models, and overall project. Feel free to:

1. Fork the repository.

2. Create a new branch.

3. Make your changes.

4. Submit a pull request.
