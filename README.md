
# Employee Attrition Prediction & Retention Strategy using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification%20%7C%20Clustering-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## Project Overview
Employee attrition significantly impacts organizational productivity, hiring costs, and knowledge continuity. 
This project develops a data-driven employee attrition prediction system using machine learning techniques to identify employees at risk of leaving and provide actionable HR retention strategies.

The solution combines Exploratory Data Analysis (EDA), classification modeling, clustering, and business insight generation to support proactive workforce planning.

---

## Business Objectives
- Predict employee attrition using supervised learning models
- Identify key factors driving employee turnover
- Segment employees into behavioral and career-based clusters
- Detect high-risk employee groups for early intervention
- Provide actionable recommendations to improve retention

---

## Dataset
The dataset includes employee demographic, compensation, performance, satisfaction, and career progression information such as:
- Demographics: Age, Gender, Education
- Job Information: Department, JobRole, JobLevel
- Compensation: MonthlyIncome, SalaryHike, StockOptions
- Satisfaction Metrics: JobSatisfaction, WorkLifeBalance, EnvironmentSatisfaction
- Career Metrics: YearsAtCompany, Promotions, YearsInCurrentRole
- Target Variable: Attrition

---

## Project Workflow

### 1. Data Preparation
- Missing value handling and feature cleaning
- Removal of constant and non-informative columns
- Categorical encoding
- Feature scaling for numerical variables

### 2. Exploratory Data Analysis
- Attrition distribution analysis
- Department and role-wise attrition trends
- Satisfaction and compensation analysis
- Correlation heatmaps and interaction analysis

### 3. Predictive Modeling
- Logistic Regression
- Random Forest Classifier

Evaluation Metrics:
- Accuracy
- Precision / Recall / F1 Score
- Confusion Matrix
- ROC-AUC

### 4. Employee Segmentation
- K-Means clustering
- PCA visualization
- Identification of high-risk employee segments

---

## Key Results
- Identified major attrition drivers including OverTime, WorkLifeBalance, and YearsSinceLastPromotion
- Random Forest achieved higher predictive performance compared to baseline models
- High-risk employee clusters identified for targeted HR interventions

---

## Business Impact
- Enables proactive attrition risk detection
- Supports HR in designing targeted retention programs
- Improves workforce planning and engagement strategy

---

## Repository Structure
```
Employee-Attrition-ML/
│
├── data/
├── notebooks/
│   └── attrition_analysis.ipynb
├── reports/
├── README.md
```

---

## Future Improvements
- Model deployment as an HR analytics dashboard
- SHAP-based explainability integration
- Real-time attrition risk monitoring

---

## Author
Sirisha Rompicherla
Machine Learning | HR Analytics Project
