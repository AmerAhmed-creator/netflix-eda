# 📊 Exploratory Data Analysis — Netflix Dataset

> Data Analysis & Visualisation Project

## 📌 Overview

A comprehensive exploratory data analysis (EDA) on a dataset of 7,000+ Netflix titles. This project uncovers viewing trends, content distribution patterns, and platform insights to support strategic content and business decisions.

---

## 🎯 Objectives

- Analyse content trends across genres, countries, and release years
- Understand the distribution of Movies vs TV Shows on the platform
- Identify patterns in content addition over time
- Visualise insights through interactive dashboards

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data loading, cleaning, manipulation |
| NumPy | Numerical operations |
| Matplotlib & Seaborn | Static visualisations |
| Power BI | Interactive dashboard |
| Jupyter Notebook | Development environment |

---

## 📁 Project Structure

```
netflix-eda/
│
├── data/
│   └── netflix_titles.csv       # Netflix dataset (from Kaggle)
│
├── notebooks/
│   └── netflix_eda.ipynb        # Full EDA notebook
│
├── dashboard/
│   └── netflix_dashboard.pbix   # Power BI dashboard file
│
├── outputs/
│   └── plots/                   # Saved visualisation images
│
├── requirements.txt
└── README.md
```

---

## 🔍 Key Analysis Areas

- **Content Type Split** — Movies vs TV Shows ratio
- **Top Countries** — Countries producing the most Netflix content
- **Genre Trends** — Most common genres on the platform
- **Release Year Trends** — How content has grown over time
- **Content Added Over Time** — Monthly/yearly addition patterns
- **Duration Analysis** — Movie lengths and TV show seasons

---

## 📈 Sample Insights

- The majority of Netflix content is Movies (~70%)
- The USA, India, and the UK are the top content-producing countries
- Content additions peaked significantly after 2016
- Drama, Comedy, and Documentary are the most common genres

---

## ▶️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/AmerAhmed-creator/netflix-eda.git
cd netflix-eda

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open the notebook
jupyter notebook notebooks/netflix_eda.ipynb
```

---

## 📦 Dataset

- Source: [Netflix Movies and TV Shows — Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- Records: 8,807 titles
- Features: title, type, director, cast, country, date_added, release_year, rating, duration, genre

---

## 📜 Requirements

```
pandas
numpy
matplotlib
seaborn
jupyter
```

---

## 👤 Author

**Amer Ahmed Mohammed**
[GitHub](https://github.com/AmerAhmed-creator) • [Email](mailto:mdamerahmedoffical@gmail.com)
