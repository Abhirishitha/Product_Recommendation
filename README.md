# Product_Recommendation

## Overview

This project uses Machine Learning techniques to analyze customer data and predict customer behavior based on demographic information, browsing history, previous purchases, and product preferences.

The project demonstrates a complete machine learning pipeline, including data preprocessing, feature encoding, model training, and performance evaluation.

---

## Dataset Features

The dataset contains the following attributes:

| Feature            | Description                  |
| ------------------ | ---------------------------- |
| Customer_ID        | Unique customer identifier   |
| Age                | Customer age                 |
| Gender             | Customer gender              |
| Location           | Customer location            |
| Income             | Annual income                |
| Browsing_History   | Customer browsing activity   |
| Previous_Purchases | Number of previous purchases |
| Preferred_Device   | Device used for shopping     |
| Product_Category   | Interested product category  |
| Time_Spent_on_Site | Time spent on the website    |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## Machine Learning Workflow

### 1. Data Preprocessing

* Loaded customer dataset
* Checked missing values
* Selected useful features
* Encoded categorical variables using **One-Hot Encoding**

```python
from sklearn.preprocessing import OneHotEncoder
```

---

### 2. Feature Encoding

Categorical columns were converted into numerical features using One-Hot Encoding.

Example:

```
Gender
↓

Male   Female

↓

Gender_Male
Gender_Female
```

---

### 3. Model Training

Two machine learning models were trained.

#### Linear Regression

```python
from sklearn.linear_model import LinearRegression

linreg_model = LinearRegression()
linreg_model.fit(a_train, b_train)
```

#### Random Forest Regressor

```python
from sklearn.ensemble import RandomForestRegressor

rf_model = RandomForestRegressor()
rf_model.fit(a_train, b_train)
```

---

## Project Structure

```
Customer-Behavior-Prediction/
│
├── customer_data.csv
├── Customer_Behavior_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## Installation
Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## Machine Learning Models

* Linear Regression
* Random Forest Regressor

---

## Libraries Used

* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn (optional)

---

## Future Improvements

* Hyperparameter tuning
* Feature selection
* Cross-validation
* XGBoost implementation
* Model deployment using Flask or FastAPI
* Interactive dashboard using Streamlit

---

## Author

**Abhirishitha Naraharisetti**

