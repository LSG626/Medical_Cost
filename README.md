# Medical Cost Prediction
Predicting medical costs using supervised machine learning.

---

## Overview

This project builds a regression model to estimate individual medical insurance charges based on demographic and health-related features.

The objective is to:

* Identify key cost drivers
* Build a predictive baseline model
* Evaluate regression performance using standard metrics

---

## Dataset

**Medical Cost Personal Dataset (Kaggle)**
Rows: 1338
Features: 7

**Input Features**

* age
* sex
* bmi
* children
* smoker
* region

**Target**

* charges

---

## Workflow

1. Data loading & inspection
2. Exploratory Data Analysis (EDA)
3. One-hot encoding of categorical variables
4. Train-test split (80/20)
5. Linear Regression modeling
6. Performance evaluation

---

## Evaluation Metrics

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

---

## Key Insight

Smoking status is the strongest predictor of insurance charges.

---

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Run Locally

```bash
git clone (https://github.com/LSG626/Medical_Cost)
cd Medical_Cost
pip install -r requirements.txt
```

---

## Future Improvements

* Cross-validation
* Tree-based models
* Hyperparameter tuning
* Target transformation
* Model explainability

---

## Author

Lesego Masehla
Aspiring Machine Learning Engineer


