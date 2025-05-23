# 🔥 Calorie Crunchers: Predicting Exercise Expenditure! 🔥

Ever wondered how many calories you *really* burn during a workout? This project dives into predicting calorie expenditure based on activity data! 🏋️‍♀️🚴‍♂️

This repository contains the Jupyter Notebook for the **Kaggle Playground Series - Season 5, Episode 5: Predict Calorie Expenditure** competition. We explore the dataset, preprocess features, and build a model to estimate those all-important burned calories.

## 🚀 What's Inside?

* **📝 `Calories_Expenditure_Prediction.ipynb`**: The heart of the project! This notebook walks you through:
    * **Data Loading & Initial Exploration**: Getting to know our `train.csv`, `test.csv`, and `sample_submission.csv`.
    * **Exploratory Data Analysis (EDA)** 📊:
        * Univariate analysis of numerical features (Age, Height, Weight, Duration, Heart Rate, Body Temp, Calories) with distribution plots (KDEs) to check for skewness and kurtosis.
        * Bivariate analysis between numerical features and the target ('Calories') using regression plots.
        * Correlation heatmaps to understand feature relationships.
        * Categorical feature ('Sex') analysis.
    * **Data Preprocessing**:
        * Handling duplicate values.
        * Checking for missing values (spoiler: none found!).
        * Encoding categorical features (`LabelEncoder` for 'Sex').
    * **Model Building & Evaluation** 🤖:
        * A range of regression models were tested (though the notebook primarily shows the setup and the final model training). These included:
            * Linear Regression
            * AdaBoost Regressor
            * Random Forest Regressor
            * KNeighbors Regressor
            * Gradient Boosting Regressor
            * XGBoost Regressor
            * LightGBM Regressor
            * CatBoost Regressor (The final chosen model for submission!)
            * Decision Tree Regressor
        * Model evaluation using **Root Mean Squared Log Error (RMSLE)**.
        * A crucial step: Ensuring predictions are non-negative using `np.maximum(0, pred)` to prevent submission errors with MSLE!
    * **Submission File Generation**: Creating the `Submission.csv` file for Kaggle.

## ✨ Key Highlights

* **Comprehensive EDA**: Visualizations and statistical summaries to understand the data's story.
* **Model Variety**: Exploration of several powerful regression techniques.
* **Focus on Metric**: Special attention to the competition's evaluation metric (RMSLE) and how to handle potential issues like negative predictions.
* **Final Model**: `CatBoostRegressor` trained on the full dataset for the final predictions.

## 💡 How to Use

1.  **Clone the repository / Download the notebook.**
2.  **Ensure you have the necessary libraries installed**: `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`, `xgboost`, `lightgbm`, `catboost`.
3.  **Place the competition data files** (`train.csv`, `test.csv`, `sample_submission.csv`) in the correct path as referenced in the notebook (or update the paths in the notebook).
    * The notebook currently uses local paths like: `C:\Users\AVIRAL\OneDrive\Desktop\PlayGround Series\playground-series-s5e5\train.csv`. You'll need to adjust these.
4.  **Run the Jupyter Notebook cells sequentially** to see the analysis, model training, and prediction generation.
5.  **The final output** will be a `Submission.csv` file ready for the Kaggle competition!

---

Let's predict those calories! Happy Kaggling! 🎉
