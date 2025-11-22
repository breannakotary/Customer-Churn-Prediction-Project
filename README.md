# Customer-Churn-Prediction-Project
Full churn prediction pipeline with EDA, feature engineering, ML modeling, and SHAP explainability. Shows end-to-end data science skills and actionable insights for reducing customer churn.

1. Project Overview

This project builds a complete end-to-end customer churn prediction system. It uses machine learning and explainable AI techniques to identify customers most likely to stop using a service, understand why they churn, and support real business decision-making.

The project demonstrates a complete data science workflow, including data ingestion, preprocessing, exploratory data analysis, modeling, model evaluation (interpretability via SHAP), and optional deployment in an interactive tool.

2. Problem Context

Customer churn is a significant business problem where customers discontinue a subscription, service, or contract. Companies in telecom, banking, SaaS, and utilities invest heavily in churn prediction tools because retaining customers is significantly more cost-effective than acquiring new ones.

This project uses a real-world public churn dataset to develop insights such as:
- Which customers are at the highest risk of churning?
- Which features contribute most to churn?
- How can the company intervene early?

3. Project Objectives

Objective 1: End-to-End Pipeline

The project replicates a production-style data science workflow, moving from raw data to a deployable model.

Objective 2: Deep Exploratory Data Analysis

The project identifies patterns in customer demographics, account data, billing behavior, and service usage. It visualizes churn differences and supports business insights.

Objective 3: Feature Engineering

Includes handling missing values, encoding categorical features, scaling numeric features, and creating domain-inspired new features. Uses a reproducible sklearn ColumnTransformer to ensure consistent preprocessing.

Objective 4: Machine Learning Modeling

Multiple algorithms are trained and compared, such as Logistic Regression and Random Forest. The evaluation uses accuracy, precision, recall, F1-score, ROC-AUC, and a confusion matrix. The best model is saved as a .pkl file.

Objective 5: Model Explainability (XAI)

SHAP values are used to generate:
- Global feature importance
- Summary plots
- Individual customer-level expectations

This allows stakeholders to understand model decisions and justify churn intervention strategies.

Objective 6: Optional Deployment

A Streamlit application can be added to allow interactive predictions and explanations for business users.

4. Skills Demonstrated

This project showcases:
- Data cleaning and transformation
- Statistical analysis and EDA
- Feature engineering and preprocessing pipelines
- Model selection and evaluation
- Explainable AI (SHAP)
- Modular Python code architecture
- Clean repo structure and documentation
- Business reasoning and stakeholder communication

5. Business Value
   
The project highlights:
- Drivers of customer churn
- Which interventions would reduce churn
- How to leverage explainability to build trust in ML models

It is practical, actionable, and aligned with honest company needs.

6. Deliverables
   
The project provides:
- A complete GitHub repository
- EDA, modeling, and explainability notebooks
- Modular Python scripts under src/
- A saved best-performing model
- SHAP explainability visualizations
- Optional Streamlit app for real-time predictions
- This detailed PDF report for documentation
