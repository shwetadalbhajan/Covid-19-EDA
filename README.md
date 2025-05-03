# 🦠 COVID-19 Exploratory Data Analysis (EDA)

This project performs an in-depth **Exploratory Data Analysis (EDA)** on the COVID-19 dataset from **Our World in Data**. It covers data wrangling, visualization, and feature engineering using Python libraries such as `pandas`, `matplotlib`, and `seaborn`.

---

## 📁 Dataset

- **Source**: [Our World in Data COVID-19](https://covid.ourworldindata.org/data/owid-covid-data.csv)
- **Features used**:
  - `location`, `date`, `total_cases`, `new_cases`, `total_deaths`, `new_deaths`, `population`

---

## 🔍 EDA Highlights

### 📊 Matplotlib
- Bar plots: Top 10 countries by cases
- Line plots: Time series of cases for selected countries
- Histograms: Distribution of daily new cases

### 🖼️ Seaborn
- Scatter plots: Population vs. Total Cases
- Box plots: Country-wise new cases
- Heatmaps: Correlation analysis
- Pairplots: Multivariate analysis

### 🧠 Pandas
- Grouping, aggregating, sorting
- Filtering by latest date
- Handling missing values

### 🧪 Feature Engineering
- Cases per million
- Death rate (% of total cases)

---

## 🛠️ Tech Stack

- Python 🐍
- pandas
- seaborn
- matplotlib
- Jupyter Notebook
