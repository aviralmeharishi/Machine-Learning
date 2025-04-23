# 🎓 Placement Prediction using Machine Learning

## 📌 Overview
This project aims to predict whether a student will be placed based on academic performance, skills, and extracurricular activities. By leveraging **Exploratory Data Analysis (EDA)**, **Descriptive Statistics**, and **Machine Learning**, this model helps students and institutions assess placement probabilities.

---

## 📂 About the Dataset
This dataset contains information about students' academic performance, skills, and placement status.

| Feature                     | Description                                                                                 | Emoticon  |
|-----------------------------|---------------------------------------------------------------------------------------------|-----------|
| **CGPA**                    | Overall grades achieved by the student.                                                     | 🎓       |
| **Internships**             | Number of internships the student has participated in.                                      | 💼       |
| **Projects**                | Number of projects the student has completed.                                               | 📚       |
| **Workshops/Certifications**| Online courses and certifications opted by students to enhance their skills.               | 🎓📜      |
| **AptitudeTestScore**       | Score obtained in aptitude tests, assessing quantitative and logical thinking.             | 🧠       |
| **SoftSkillRating**         | Rating for communication skills, essential for placements and professional growth.         | 💬       |
| **ExtraCurricularActivities** | Reflects the student's engagement in activities outside of academics.                      | ⚽🎭      |
| **Placement Status (Target)** | Whether the student got placed (1) or not (0).                                           | ✅❌      |

---

## 📊 Exploratory Data Analysis (EDA)
Key steps performed during **EDA** include:
- **Handling Missing Values**
- **Descriptive Statistics** (Mean, Median, Mode, Variance)
- **Feature Distributions & Correlations**
- **Outlier Detection & Treatment**
- **Visualizations** using Matplotlib & Seaborn:
  - CGPA vs. Placement Status 📈
  - Internships vs. Placement 📊
  - Aptitude Score Distribution 📉
  - Soft Skills vs. Placement 📊

---

## 🚀 Machine Learning Pipeline
The dataset was used to train and evaluate various **classification models** to predict student placements.

### 🔹 **Feature Engineering**
- Normalization & Scaling
- One-Hot Encoding (if applicable)
- Feature Selection

### 🔹 **Models Implemented**
1. **Logistic Regression**
2. **Random Forest**
3. **XGBoost**
4. **Naive Bayes**

### 🔹 **Model Evaluation**
- **Accuracy:** 80.04%
- **Precision:** 70.40%
- **Recall:** 80.45%
- **F1-score:** 77.42%
- **ROC-AUC Score:** 0.87

📌 **Best Model**: Bernaulli's Naive Bayes

---

## 🎯 Deployment
The trained model is deployed using **Streamlit** for easy interaction.

---

## 📎 Installation & Usage
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/aviralmeharishi/placement-prediction.git
cd placement-prediction
