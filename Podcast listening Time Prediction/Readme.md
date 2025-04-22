# 🎙️ Podcast Popularity Insights 📊

Welcome to the **Podcast Popularity Insights** project – where data meets the dynamic world of podcasts! Dive into a dataset packed with features about episodes, genres, host and guest popularity, listener behavior, and more. Our goal? To uncover what makes an episode *pop* with popularity! 🔥

---

## 🚀 Project Overview

This project explores a rich dataset of podcast episodes and applies data cleaning, feature engineering, and imputation techniques to make it model-ready. With features like **Episode Length**, **Genre**, **Guest & Host Popularity**, and **Sentiment**, we analyze and prepare the data for deeper insights and potential modeling.

---

## 🔍 Key Highlights

- ✅ **Missing Value Imputation** using:
  - Mean and Median (via `SimpleImputer`)
  - Genre-wise Average (smart contextual filling 🎯)
  - Advanced options like KNN Imputer (optional)

- 🧼 **Data Cleaning & Transformation**
  - Handled nulls in key columns like `Guest_Popularity_percentage`
  - Encoded categorical data for modeling ease
  - Feature extraction from timestamps

- 📈 Ready for:
  - Regression or Classification modeling
  - Sentiment impact studies
  - Recommender Systems

---

## 🧠 Technologies Used

- Python 🐍
- Pandas & NumPy
- Scikit-Learn
- Matplotlib / Seaborn (for EDA & visuals)
- Jupyter Notebook

---

## 📁 Dataset Features

| Feature Name                | Description                                      |
|----------------------------|--------------------------------------------------|
| `Podcast_Name`             | Name of the podcast                              |
| `Episode_Title`            | Title of the episode                             |
| `Episode_Length_minutes`   | Duration in minutes                              |
| `Genre`                    | Genre of the episode                             |
| `Host_Popularity_percentage` | Popularity of the host                        |
| `Guest_Popularity_percentage` | Popularity of the guest                     |
| `Number_of_Ads`            | Number of ads in the episode                     |
| `Episode_Sentiment`        | Sentiment score of the episode                   |
| `Listening_Time_minutes`   | Average time a listener spent on the episode     |

---

## 📊 Insights & Ideas 💡

- Do longer episodes really perform better?
- Does guest popularity correlate with listening time?
- How does sentiment influence popularity?

---

## 📌 Next Steps

- 🤖 Build ML models to predict listening time
- 📢 Recommend best days/times to publish
- 🎧 Analyze optimal ad placement

---

## 👨‍💻 Author

**Aviral Meharishi**  
🔗 [GitHub](https://github.com/aviralmeharishi)  
📫 aviralmeharishi@gmail.com  


---

## 📝 License

This project is licensed under the MIT License.

---

> *“In a world of noise, your data tells the story.”* 📚  
