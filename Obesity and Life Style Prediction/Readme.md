# 💪 BodyScope: Obesity Risk Predictor with ML + Gemini AI

> 🔬 *"Transforming data into wellness."*  
> A full-stack intelligent health companion that predicts **your obesity risk** using machine learning — and gives you **personalized Gemini AI advice** in both **English and Hindi**. Built with ♥ by [Aviral Meharishi](https://www.linkedin.com/in/aviralmeharishi/).

---

## 🚀 [Try the App Live](https://bodyscope.streamlit.app/)  

🩺 Enter your health and lifestyle info  
🔍 Get your obesity risk instantly  
🤖 Receive smart health suggestions powered by **Gemini AI**

---

## 🔧 What Makes BodyScope Unique?

| ✅ Feature | 🔍 Description |
|-----------|----------------|
| 📊 **End-to-End ML Pipeline** | Cleaned, encoded, scaled, and modeled real-world data |
| 🧠 **Model Accuracy** | `RandomForestClassifier` with **89% accuracy** |
| 🤖 **Gemini AI Advice** | Personalized, bilingual (English + Hindi) health tips |
| 🌈 **Streamlit Interface** | Lightweight, fast, and deployed for real-time use |
| 🧪 **Statistical Insights** | Hypothesis-tested feature selection for explainability |

---

## 🔁 ETL + Modeling Workflow

- **Extract**: Loaded raw `.csv` dataset  
- **Transform**:  
  - Categorical encoding (Label + Ordinal)  
  - Handled special mappings (e.g., `Smoking Frequency`)  
  - Feature relevance via correlation + hypothesis tests  
- **Load**:  
  - Train/test split using `StratifiedShuffleSplit`  
  - Model training & tuning  
  - Saved as `final_model.pkl`

---

## 📈 ML Model Leaderboard

| Model                | Accuracy | F1 Score |
|---------------------|----------|----------|
| 🥇 Random Forest     | **0.89** | **0.87** |
| 🥈 XGBoost           | 0.87     | 0.84     |
| 🥉 Logistic Regression | 0.76   | 0.75     |

✅ **Final Pick**: Random Forest

---

## 🤖 Gemini AI Health Suggestions

Get context-aware, bilingual tips like:

> _"Based on your BMI and activity levels, try switching to fiber-rich foods and walk 30 mins daily."_  
> _"आपका वजन अधिक है। मीठा कम करें और हफ्ते में कम से कम 5 दिन व्यायाम करें।"_

Powered by **Google's Gemini API**, built to inspire a healthier you.

---

## 🛠 Tech Stack

- 🐍 **Python**, `Pandas`, `NumPy`, `Seaborn`, `Matplotlib`  
- 🔍 `Scikit-learn`, `XGBoost`, `RandomForestClassifier`  
- 🤖 `Gemini Generative AI` (via `google.generativeai`)  
- 🌐 `Streamlit` for UI  
- 🧊 `Pickle` for model storage  

---

## 📬 Let’s Connect!

- 💼 [LinkedIn – Aviral Meharishi](https://www.linkedin.com/in/aviralmeharishi/)
- 💻 [GitHub – aviralmeharishi](https://github.com/aviralmeharishi)
- 📧 aviralmeharishi@gmail.com

---

> ⚠️ **Disclaimer**: BodyScope is an AI-based health assistant and not a medical diagnostic tool. For any serious health concerns, consult a licensed physician.

