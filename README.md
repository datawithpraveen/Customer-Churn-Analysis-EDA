# Customer-Churn-Analysis-EDA

- **Target Variable**: `Churn`
- **Type**: Classification Problem

---

## 🔍 Objectives

- Identify patterns and trends among customers who have churned.
- Understand the impact of demographic, service, and billing features on churn.
- Visualize the most influential factors to support business decisions.

---

## 🛠️ Tools & Technologies

- **Python (Jupyter Notebook)**
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`
- Visualization: Seaborn plots, heatmaps, bar charts

---

## 🧹 Data Preprocessing

- Checked for **null and missing values**
- Converted categorical variables to appropriate formats
- Cleaned `TotalCharges` (which may have had non-numeric values)
- Ensured all features were in usable format for analysis

---

## 📊 Exploratory Data Analysis (EDA)

### ✔️ Univariate Analysis
- Examined distribution of individual features (e.g., gender, tenure, MonthlyCharges)

### ✔️ Bivariate Analysis
- Compared `Churn` with categorical and numerical variables
- Explored patterns like:
  - Contract type vs. Churn
  - MonthlyCharges vs. Churn
  - Tenure vs. Churn

### ✔️ Correlation Analysis
- Generated a heatmap to show correlation between numeric variables
- Analyzed multicollinearity and feature importance

---

## 📈 Visualizations

- Bar charts and count plots (e.g., Churn by Contract Type)
- Histograms for distributions (e.g., MonthlyCharges)
- Heatmap for correlation matrix
- Boxplots to compare churn across numerical values

---



## 📎 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/customer-churn-analysis.git
