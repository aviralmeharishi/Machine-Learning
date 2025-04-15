# 🌍 Country Data Segmentation Using Socio-Economic Factors

## ✨ Project Summary

HELP International, a humanitarian NGO, has raised **$10 million** to support countries in need. Your mission as a data scientist is to **analyze, cluster, and segment countries** based on socio-economic and health indicators to identify those most in need of aid.

---

## 📁 Dataset Overview

The dataset includes **167 countries** and **10 attributes**, measuring indicators like child mortality, GDP, healthcare spending, and life expectancy.

### 📊 Data Description Table

| Column Name  | Description                                                                 |
|--------------|-----------------------------------------------------------------------------|
| country      | Name of the country                                                         |
| child_mort   | Deaths of children under 5 years of age per 1000 live births               |
| exports      | Exports of goods and services as a percentage of GDP                       |
| health       | Total health spending as a percentage of GDP                               |
| imports      | Imports of goods and services as a percentage of GDP                       |
| income       | Net income per person                                                       |
| inflation    | Annual inflation rate (%)                                                   |
| life_expec   | Average life expectancy of citizens                                         |
| total_fer    | Fertility rate, i.e., the number of children per woman                      |
| gdpp         | GDP per capita                                                              |

---

## 🧠 Objective

- Segment countries based on development indicators.
- Use clustering algorithms (KMeans) to group countries into development clusters.
- Recommend the **most underdeveloped cluster** that needs urgent aid.
- Build a prediction tool that allows entering new data and identifying its cluster.

---

## 🚀 Tech Stack & Tools

- **Python**
- **Pandas**, **NumPy**
- **Seaborn**, **Matplotlib**, **Plotly**
- **Scikit-learn** (KMeans, PCA, StandardScaler)
- **Yellowbrick** (Silhouette & Elbow visualizers)
- **Streamlit** *(for deployment - optional)*

---

## 🔍 Exploratory Analysis

- Conducted data profiling and visualized distributions of key variables.
- Normalized features for fair clustering.
- Applied PCA to reduce dimensionality and improve interpretability.

---

## 🔗 Procedure to Run

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook "Country Data Segmentation Using Socio Economic factors.ipynb"
```
