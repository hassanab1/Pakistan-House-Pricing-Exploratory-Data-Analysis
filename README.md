# 🏠 Pakistan House Pricing — Exploratory Data Analysis

A hands-on EDA project exploring house pricing trends in Pakistan using a Kaggle dataset. The goal is to uncover patterns in property prices across different cities, sizes, and features.

---

## 📁 Project Structure

```
├── House pricing.ipynb   # Main Jupyter Notebook
├── dataset/
│   └── pk_house_pricing.csv  # Kaggle dataset
└── README.md
```

---

## 🛠️ Tools & Libraries

| Library | Purpose |
|--------|---------|
| `pandas` | Data loading, cleaning & manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Base plotting & visualizations |
| `seaborn` | Statistical plots & heatmaps |

---

## 📊 Project Overview

This project performs a full exploratory data analysis on a Pakistan house pricing dataset sourced from Kaggle. The workflow is broken into 5 structured phases:

### ⚙️ Initial Setup & Data Loading
Imported all necessary libraries for computation and visualization — `pandas`, `numpy`, `matplotlib`, and `seaborn`.

### 🔎 Phase 1 — Data Inspection
Examined the dataset's structure to understand the volume and types of data: shape, dtypes, null counts, and a first look at sample records.

### 🧹 Phase 2 — Data Cleaning & Preprocessing
Refined the dataset by:
- Removing irrelevant or redundant features
- Handling missing values
- Eliminating duplicate records

### 🔧 Phase 3 — Feature Engineering
Transformed raw data into more meaningful features, including:
- Standardizing area units (e.g., Marla, Kanal → a common unit)
- Formatting and parsing date columns for time-based analysis

### 📈 Phase 4 — Exploratory Data Analysis (EDA)
Created new metrics to analyze market value and property characteristics, including distribution plots, correlation heatmaps, and city/location-based comparisons.

---

## 🔍 Key Findings

- **Location is the strongest price driver** — Properties in Islamabad and Lahore DHA command significantly higher prices compared to other areas.
- **Price scales non-linearly with area** — Larger properties don't always fetch proportionally higher prices; neighborhood matters more.
- **Bedrooms vs. Price** — 3–4 bedroom houses represent the most common and competitively priced segment.
- **Significant outliers exist** — A small number of luxury listings skew the mean price considerably; median is a more reliable central measure.
- **Data imbalance across cities** — Karachi and Lahore dominate the listings, which may bias city-level comparisons.

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/hassanab1/Pakistan-House-Pricing-Exploratory-Data-Analysis.git
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook eda_house_pricing.ipynb
   ```

---

## 📦 Dataset

- **Source:** [Kaggle — Pakistan House Pricing Dataset](https://www.kaggle.com/datasets/jillanisofttech/pakistan-house-price-dataset)
- Contains listings with features like city, location, area (marla/sqft), bedrooms, bathrooms, and price.

---

## 👤 Author

**Your Name**
- GitHub: [@hassanab1]([https://github.com/your-username](https://github.com/hassanab1/)

---

*This project is part of my data science practice portfolio.*
