# Predictive Analytics Using Historical Data

A machine learning project that builds predictive models to forecast **California house prices** using regression techniques. Trained on 20,640 real-world samples with full data preprocessing, model evaluation, and visualization.

---

## Project Overview

| Item | Details |
|---|---|
| Dataset | California Housing (scikit-learn) |
| Task | Regression — predict house prices |
| Models | Linear Regression, Random Forest Regressor |
| Best Model | Random Forest — R² Score: **0.8050** |
| Tools | Python, scikit-learn, Pandas, Matplotlib, Seaborn |

---

## Key Features

- **Data Cleaning & EDA** — checked for missing values, visualized price distribution and feature correlations via heatmap
- **Feature Scaling** — applied `StandardScaler` to normalize all 8 input features
- **Model Training** — compared Linear Regression vs Random Forest Regressor
- **Model Evaluation** — measured R² Score and RMSE on test data
- **Visualization** — 4 charts: Actual vs Predicted, Feature Importance, Residuals Distribution

---

## Results

| Model | R² Score | RMSE |
|---|---|---|
| Linear Regression | 0.5758 | 0.7456 |
| Random Forest | **0.8050** | **0.5055** |

Random Forest outperforms Linear Regression with **80.5% variance explained**.

---

## Project Structure

```
Predictive_Analytics/
│
├── Predictive_Analytics.ipynb   # Main notebook (7 cells)
└── README.md
```

---

## How to Run

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload `Predictive_Analytics.ipynb`
3. Click **Runtime → Run All**

All libraries (pandas, numpy, scikit-learn, matplotlib, seaborn) are pre-installed in Colab.

---

## Libraries Used

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

## Author

**Rethesh** — CSE undergraduate, Sona College of Engineering and Technology  
Internship Task 3 — Thiranex Skill Development Program
