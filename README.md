# Customer-Churn-Analysis-Report

## Overview

This end-to-end project aims to analyze and predict customer churn using Python and visualize key business insights through an interactive Power BI dashboard. The analysis empowers businesses to understand why customers leave and how to mitigate churn effectively.

---

## 🧾 Project Structure

```text
├── Churn Analysis - EDA.ipynb             # Data exploration & insights
├── Churn Analysis - Model Building.ipynb  # Machine Learning pipeline
├── churnDashboard.pbix                    # Power BI dashboard for stakeholders
├── README.md                              # Project documentation
```

---

## 🎯 Objective

- Understand key behavioral and patterns that influence churn.
- Build predictive models to estimate churn likelihood.
- Deliver actionable insights via a business-friendly dashboard.

---

## 🔍 Exploratory Data Analysis (EDA)

Notebook: `Churn Analysis - EDA.ipynb`

Main tasks:
- Data cleaning and handling missing values
- Visualization of categorical and numerical features
- Correlation analysis and customer segmentation
- Initial churn distribution and patterns

Key libraries: `Pandas`, `Seaborn`, `Matplotlib`, `Plotly`

---

## 🤖 Machine Learning Model

Notebook: `Churn Analysis - Model Building.ipynb`

Steps:
- Data preprocessing (label encoding, train-test split)
- Training multiple models (Logistic Regression, Random Forest, XGBoost)
- Evaluation using accuracy, precision, recall, F1-score, ROC AUC
- Confusion matrix and model tuning with GridSearchCV

### ✅ Best Model Performance (Random Forest Classifier):

| Metric        | Value   |
|---------------|---------|
| Accuracy      | **94.27%** |
| Precision     | 0.95 (Class 0), 0.94 (Class 1) |
| Recall        | 0.92 (Class 0), 0.96 (Class 1) |
| F1-Score      | 0.93 (Class 0), 0.95 (Class 1) |
| Confusion Matrix | `[[478, 40], [27, 625]]` |

The model is able to correctly classify most churners and non-churners with high accuracy and balanced precision/recall.

---

## 📈 Power BI Dashboard

File: `churnDashboard.pbix`

Interactive visualizations include:
- Churn rate by customer type and demographics
- Monthly churn trend
- KPIs (e.g., total customers, churn %, active users)
- Feature impact analysis

Business Use:
- Designed for stakeholder consumption
- Helps identify at-risk customer segments
- Supports decision-making for churn reduction strategies

---

## ⚙️ Tech Stack

- **Python** (Pandas, Scikit-learn, Random Forest, Matplotlib)
- **Jupyter Notebook**
- **Power BI Desktop**
- **GitHub** for version control and collaboration

---

## 🚀 How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/churn-analysis.git
   cd churn-analysis
   ```

2. Run the notebooks:
   - `Churn Analysis - EDA.ipynb`
   - `Churn Analysis - Model Building.ipynb`

3. Open `churnDashboard.pbix` in Power BI Desktop to explore insights.

---

## 📚 Conclusion

This project provides a comprehensive churn analysis pipeline—starting from raw data exploration to predictive modeling and dashboarding. It showcases how data science can generate business value by reducing customer attrition.

---

## 📬 Contact

For queries or collaborations, feel free to reach out on [LinkedIn-www.linkedin.com/in/rai-adarsh] or email: `adarshjanardhanrai@gmail.com`
