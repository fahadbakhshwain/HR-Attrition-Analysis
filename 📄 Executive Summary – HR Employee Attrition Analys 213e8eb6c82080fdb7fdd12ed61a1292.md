# 📄 Executive Summary – HR Employee Attrition Analysis

## 📄 Executive Summary – HR Employee Attrition Analysis

### 🎯 Objective

The goal of this project was to analyze employee attrition data and build a predictive model to help the company identify key factors contributing to attrition. This enables HR and leadership teams to implement strategic actions to improve retention and reduce recruitment costs.

---

### 🔍 Project Overview

We used a dataset of 1,470 employees from a multinational company, covering features such as employee satisfaction, department, income, job role, years at company, and more. We built and evaluated several machine learning models including Logistic Regression, Random Forest, and XGBoost.

After model comparison and hyperparameter tuning, **XGBoost** achieved the best balance of accuracy and interpretability.

---

### 📊 Model Performance

- ✅ **Model Used:** XGBoost (with GridSearchCV tuning)
- **Accuracy:** 84.7%
- **Precision:** 57.1%
- **Recall:** 17%
- **F1 Score:** 26.2%

This model is better at precision (identifying actual leavers), but the recall is relatively low, meaning we still miss some leavers. However, it’s suitable for identifying the **most at-risk employees**.

---

### 🧠 Top Features Influencing Attrition

Below are the most important features in predicting whether an employee will leave:

| Feature | Importance |
| --- | --- |
| Relationship Satisfaction | 6.1% |
| Job Role: Manager | 5.6% |
| Job Role: Sales Representative | 5.2% |
| Job Role: Manufacturing Director | 4.2% |
| Job Role: Lab Technician | 4.0% |
| Performance Rating | 3.9% |
| Age | 3.4% |
| Years at Company | 3.3% |
| Education Field: Marketing | 3.1% |
| Employee Count (redundant) | 2.9% |

---

### 📌 Key Insights

1. **Job Role** plays a significant part in attrition. Sales Representatives and Lab Technicians are at higher risk.
2. Employees with **low relationship satisfaction** are more likely to leave.
3. **Performance rating** and **career progression** (such as Years at Company) are contributing factors.
4. Marketing field employees are showing signs of dissatisfaction.

---

### ✅ Recommendations

Based on the analysis, we recommend the following:

1. **Prioritize High-Risk Roles**
    - Conduct focused engagement interviews with Sales and Lab employees.
    - Evaluate if training, promotion tracks, or incentives need adjustment.
2. **Boost Relationship Satisfaction**
    - Launch internal mentorship or wellness programs.
    - Measure relationship satisfaction in monthly feedback.
3. **Monitor High Performers Closely**
    - Some employees with high performance are still leaving, which may indicate **lack of recognition or promotion.**
4. **Review Marketing Department Dynamics**
    - Their dissatisfaction may relate to role clarity, growth, or expectations.