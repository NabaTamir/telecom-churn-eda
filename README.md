# Telecom Customer Churn – Exploratory Data Analysis
## Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on a telecommunications customer dataset to identify key factors influencing customer churn.

The objective is to understand customer behavior patterns prior to predictive modelling and to derive actionable business insights.

Customer churn prediction is a critical business problem, as retaining existing customers is typically more cost-effective than acquiring new ones.


## Dataset
This project uses the **Telco Customer Churn Dataset** available on Kaggle:

https://www.kaggle.com/blastchar/telco-customer-churn
To run the notebook:

1. Download the dataset from Kaggle
2. Create a `data/` folder inside this repository
3. Place `churn.csv` inside the `data/` directory

Expected structure:

```
telecom-churn-eda/
│
├── 01_Telecom_Churn_EDA.ipynb
├── README.md
└── data/
    └── churn.csv
```

##  EDA Objectives
The exploratory analysis focuses on:

* Understanding dataset structure and feature types
* Identifying missing values and duplicates
* Analysing numerical feature distributions
* Evaluating categorical variable patterns
* Assessing class imbalance
* Investigating relationships between predictors and churn

## Key Insights
* **Churn Rate:** ~27% (moderate class imbalance)
* **Tenure:** Short tenure strongly associated with higher churn
* **Contract Type:** Month-to-month customers show significantly higher churn
* **Monthly Charges:** Higher monthly costs increase churn likelihood
* **Payment Method:** Electronic check users have elevated churn rates
* **Service Add-ons:** OnlineSecurity and TechSupport reduce churn probability
* **Internet Type:** Fiber optic customers exhibit higher churn rates



## Important Observations
* `tenure` and `TotalCharges` are strongly correlated
* Customers with longer contracts demonstrate stronger retention
* Churned customers tend to have higher monthly charges but lower total charges (shorter service duration)


## Tools Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Missingno
* Statsmodels


## Next Steps
* Feature engineering
* Categorical feature encoding
* Handling class imbalance
* Model development (Logistic Regression, Random Forest, XGBoost)
* Performance evaluation using ROC-AUC and F1-score



## Author
Naba Tamir
Master of Data Science (Predictive Analytics)
Curtin University

