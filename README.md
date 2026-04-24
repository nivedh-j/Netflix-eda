# 🎬 Netflix Content Analysis — Exploratory Data Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the [Netflix Movies and TV Shows dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows) to uncover patterns and insights about Netflix's global content strategy.

The analysis covers:
- 📊 Content type distribution (Movies vs TV Shows)
- 🌍 Country-wise production breakdown
- 📅 Release year trends (2008–2024)
- 🎭 Genre popularity by content type
- ⭐ Ratings distribution
- 🧹 Data cleaning and handling missing values

---

## 🔍 Key Findings

| Question | Insight |
|---|---|
| Movies vs TV Shows | Movies dominate Netflix's library (~70%) |
| Top Producing Country | 🇺🇸 United States leads in both Movies and TV Shows |
| Peak Content Years | 2017–2020 saw the highest content additions |
| Top Movie Genre | International Movies → Dramas → Comedies |
| Top TV Show Genre | International TV Shows → TV Dramas → TV Comedies |
| Content Trend | Steady growth post-2015 for both types |

---

## 📁 Repository Structure

```
netflix-eda/
│
├── 📓 notebooks/
│   └── EDA_Netflix.ipynb          # Main Jupyter Notebook
│
├── 📂 data/
│   └── netflix_titles.csv         # Raw dataset (from Kaggle)
│
├── 🖼️ images/
│   └── *.png                      # Exported plots & visualizations
│
├── 📄 requirements.txt            # Python dependencies
├── 📄 .gitignore
└── 📄 README.md
```

---

## 🛠️ Tech Stack

| Library | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Static visualizations |
| `seaborn` | Statistical plots |
| `plotly` | Interactive charts |

---

---

## 📊 Visualizations Preview

### Content Type Distribution
> ~70% of Netflix content consists of Movies, with TV Shows making up the remainder.

### Top 10 Countries by Content Volume
> The US, India, and UK are the top three content-producing countries on Netflix.

### Content Growth Over Time
> Both Movies and TV Shows show a strong upward trend from 2015 to 2024.

### Genre Breakdown
> International content dominates both categories, reflecting Netflix's global expansion strategy.

---

## 📈 Analysis Workflow

```
1. Load Data
      ↓
2. Inspect & Understand (shape, dtypes, nulls)
      ↓
3. Handle Missing Values (drop unnamed cols, fill/drop nulls)
      ↓
4. Fix Incorrect Entries (ratings corrections)
      ↓
5. Feature Engineering (split multi-country entries)
      ↓
6. EDA & Visualizations (6+ questions answered)
      ↓
7. Insights & Takeaways
```

---

## 🧩 Questions Explored

1. **What type of content dominates Netflix?** (Movies vs TV Shows)
2. **Which countries produce the most Netflix content?**
3. **When did Netflix add the most content?** (Year-wise trend)
4. **What genres dominate Movies?**
5. **What genres dominate TV Shows?**
6. **How has content volume grown over time?** (Trend lines)

---

## 📂 Dataset

- **Source**: [Kaggle — Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Size**: ~8,800 titles
- **Columns**: `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

> ⚠️ The dataset is **not included** in this repo due to size. Please download it from Kaggle.

---

## 🙋 Author

**Nivedh J**
- 📧 [LinkedIn](https://www.linkedin.com/in/nivedhj)
- 🐙 [GitHub](https://github.com/nivedh-j)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

*If you found this project useful, please consider giving it a ⭐ — it helps others find it!*
