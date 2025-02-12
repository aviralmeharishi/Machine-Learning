# Loan Prediction Model 🚀

## 📌 Project Overview
This project aims to predict whether a customer will accept a personal loan offer based on their demographic and financial information. We have performed data cleaning, exploratory data analysis (EDA), and model building, finalizing a tuned XGBoost model as the best-performing classifier.

## 🗂 Data Description

| Column Name         | Description |
|---------------------|-------------|
| **ID**             | Customer ID |
| **Age**            | Customer's age in completed years |
| **Experience**     | # years of professional experience |
| **Income**         | Annual income of the customer ($000) |
| **ZIPCode**        | Home Address ZIP code |
| **Family**         | Family size of the customer |
| **CCAvg**          | Avg. spending on credit cards per month ($000) |
| **Education**      | Education Level. 1: Undergrad; 2: Graduate; 3: Advanced/Professional |
| **Mortgage**       | Value of house mortgage if any ($000) |
| **Personal Loan**  | Did this customer accept the personal loan offered in the last campaign? |
| **Securities Account** | Does the customer have a securities account with the bank? |
| **CD Account**     | Does the customer have a certificate of deposit (CD) account with the bank? |
| **Online**         | Does the customer use internet banking facilities? |
| **CreditCard**     | Does the customer use a credit card issued by UniversalBank? |

## 🛠 Data Cleaning
- 🧹 Handled missing values (if any) by imputation or removal.
- 🔄 Removed duplicate entries to ensure data integrity.
- 🔢 Converted categorical variables into numerical representations.
- 📊 Standardized numerical features for better model performance.

## 📊 Exploratory Data Analysis (EDA)
- 📉 Visualized the distribution of key numerical features such as age, income, and credit card spending.
- 🔍 Analyzed the correlation between features to identify important predictors.
- 📈 Examined the distribution of the target variable (Personal Loan acceptance).

## 🤖 Model Building
- 🏗 Tried multiple models including Logistic Regression, Decision Tree, Random Forest, and XGBoost.
- 🎯 Tuned hyperparameters using GridSearchCV for the best-performing model.
- 📊 Evaluated models using accuracy, precision, recall, and F1-score.
- ✅ **Final Model Selected:** Tuned **XGBoost**, which provided the highest predictive accuracy.

## 🔮 Next Steps
- 🔧 Further feature engineering to improve performance.
- 🌍 Implementing model deployment using a web application.
- ✅ Testing the model on real-world customer data for validation.

## ⚠️ Disclaimer
This project is developed for educational purposes, and all rights and credits for the dataset and learning resources go to **Great Learning**. This work is inspired by their course materials and datasets used for training and skill enhancement. 🚀

