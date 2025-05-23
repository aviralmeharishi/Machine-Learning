## 📊 Data Description

The dataset for this project aims to predict calorie expenditure. It consists of the following features:

* **`id`**: A unique identifier for each record.
* **`Sex`**: The gender of the individual (Categorical: male/female). Encoded into numerical format (0 or 1) during preprocessing.
* **`Age`**: The age of the individual in years (Numerical: `int64`).
* **`Height`**: The height of the individual in centimeters (Numerical: `float64`).
* **`Weight`**: The weight of the individual in kilograms (Numerical: `float64`).
* **`Duration`**: The duration of the exercise/activity in minutes (Numerical: `float64`).
* **`Heart_Rate`**: The average heart rate of the individual during the activity (Numerical: `float64`).
* **`Body_Temp`**: The body temperature of the individual during the activity in Celsius (Numerical: `float64`).

### Target Variable:

* **`Calories`**: The number of calories expended by the individual (Numerical: `float64`). This is the value our model aims to predict.

The training data (`train.csv`) contains all the features listed above, including the `Calories` target variable. The test data (`test.csv`) contains all features except for `Calories`. A `sample_submission.csv` provides the format for submission.
