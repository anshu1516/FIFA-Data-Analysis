# ⚽ FIFA 20 — Player Data Analysis using Python

An exploratory data analysis of the **FIFA 20 player dataset**, covering nationality distributions, player wages, physical attributes, shooting, defending skills, and a deep dive into **Real Madrid** and **Germany** squads.

---

## 📌 Project Overview

This project explores the FIFA 20 complete player dataset (`players_20.csv`) containing **18,278 players** across **144 attributes**. The analysis uncovers top nationalities, highest-paid players, best shooters and defenders, and provides club and country-level breakdowns.

---

## 📂 Dataset

- **Source:** [Kaggle — FIFA 20 Complete Player Dataset](https://www.kaggle.com/datasets/stefanoleone992/fifa-20-complete-player-dataset)
- **File used:** `players_20.csv`
- **Size:** 18,278 players × 144 attributes

---

## 🔍 Analysis Breakdown

### 🌍 Nationality Analysis
- Count of players by nationality
- Top 10 most represented nationalities
- Bar chart of top 5 nationalities in FIFA 20

### 💰 Player Wages
- Extracted and sorted players by weekly wage (EUR)
- Bar chart of the **top 5 highest-paid players** in the game

### 🇩🇪 Germany Squad Deep Dive
- Filtered all German players from the dataset
- Top German players by:
  - Height (cm)
  - Weight (kg)
  - Weekly wage (EUR)

### 🎯 Skill Rankings
- **Top shooters** — players ranked by shooting attribute
- **Top defenders** — players ranked by defending attribute (with club & nationality)

### 🏟️ Real Madrid Club Analysis
- Filtered all Real Madrid players
- Ranked by:
  - Weekly wage
  - Shooting ability
  - Defending ability
- Nationality breakdown of the Real Madrid squad

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3 | Core language |
| Pandas | Data loading & manipulation |
| Matplotlib | Bar charts & visualizations |
| Seaborn | Statistical plotting |
| Google Colab | Development environment |

---

## 🚀 How to Run

### Option 1 — Open in Google Colab
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

*(Replace with your actual Colab notebook link)*

### Option 2 — Run Locally
```bash
git clone https://github.com/anshu1516/FIFA-Data-Analysis.git
cd FIFA-Data-Analysis

pip install pandas matplotlib seaborn

jupyter notebook Python_project_on_FIFA.ipynb
```

> **Note:** Download `players_20.csv` from Kaggle and place it in the same directory before running.

---

## 💡 Key Insights

- **England, Germany, Spain, France, and Argentina** are the most represented nationalities in FIFA 20
- A handful of elite players earn significantly more than the rest of the dataset
- **Real Madrid** has one of the most internationally diverse squads in the game

---

## 👤 Author

**Anshu** — [GitHub](https://github.com/anshu1516)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
