<div align="center">

# ❤️ Heart Disease EDA

**Exploratory data analysis on the UCI Heart Disease dataset — uncovering patterns behind heart disease risk.**

[![Python](https://img.shields.io/badge/Python-3.10-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![pandas](https://img.shields.io/badge/pandas-Data-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![seaborn](https://img.shields.io/badge/seaborn-Visualization-4C72B0)](https://seaborn.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[Overview](#-overview) •
[What's Inside](#-whats-inside) •
[Dataset](#-dataset) •
[Getting Started](#-getting-started) •
[Author](#-author)

</div>

---

## 📖 Overview

A beginner-friendly EDA project on the [UCI Heart Disease dataset](https://archive.ics.uci.edu/dataset/45/heart+disease) — 303 patient records with 13 clinical features. No modeling here, just structured exploration: inspecting the data, visualizing distributions, and comparing features against heart disease status.

---

## 🔍 What's Inside

- **Basic inspection** — shape, data types, missing values, duplicates
- **Target distribution** — checking class balance (disease vs. no disease)
- **Univariate analysis** — histograms and boxplots for numeric features, count plots for categorical ones
- **Bivariate analysis** — how each feature (age, chest pain type, max heart rate, etc.) relates to heart disease status
- **Correlation heatmap** — which features are most strongly linked to the target

---

## 📊 Dataset

| Column | Meaning |
|---|---|
| age | Age in years |
| sex | 1 = male, 0 = female |
| cp | Chest pain type (0–3) |
| trestbps | Resting blood pressure (mm Hg) |
| chol | Serum cholesterol (mg/dl) |
| fbs | Fasting blood sugar > 120 mg/dl |
| restecg | Resting ECG results (0–2) |
| thalach | Maximum heart rate achieved |
| exang | Exercise-induced angina |
| oldpeak | ST depression induced by exercise |
| slope | Slope of peak exercise ST segment |
| ca | Number of major vessels colored by fluoroscopy |
| thal | Thalassemia type |
| target | 1 = heart disease, 0 = no heart disease |

---

## 📁 Project Structure

```
Heart-Disease-EDA/
│
├── Heart_Disease_EDA.ipynb    # full EDA notebook
├── requirements.txt
├── LICENSE
└── README.md
```

---

## 🛠️ Tech Stack

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Jupyter`

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/ibrahimkhan-data/Heart-Disease-EDA.git
cd Heart-Disease-EDA
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
```bash
jupyter notebook Heart_Disease_EDA.ipynb
```
The dataset is loaded directly from a public URL inside the notebook, so no separate download is needed.

---

## 👤 Author

**Khan Ibrahim**

B.Tech — Artificial Intelligence & Data Science

[![GitHub](https://img.shields.io/badge/GitHub-ibrahimkhan--data-181717?logo=github&logoColor=white)](https://github.com/ibrahimkhan-data/)

---

## License

This project is licensed under the [MIT License](LICENSE).
