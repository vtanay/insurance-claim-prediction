# 🚗 Insurance Claim Prediction – Final Project Notebook

This project focuses on building a classification model to predict whether a customer will file a **car insurance claim** during the policy period. Designed for "On the Road" insurance, the objective is to assist the company in **better estimating consumer behavior and potential claim risk**, ultimately leading to improved pricing and cost management.

## 🧠 Project Overview

In the competitive and regulated world of car insurance, accurate claim prediction is critical. This notebook walks through a complete **machine learning workflow**, including:

- Data loading and cleaning
- Exploratory data analysis (EDA)
- Feature engineering
- Model training and evaluation
- Comparison of multiple classification models

## 🗃️ Dataset Information

- **Total Rows:** 10,000
- **Features:** 18
- **Target Variable:** Binary indicator of whether a claim was made
- **Feature Types:**
  - **Numeric:** Age, Income, Credit Score, Annual Mileage
  - **Categorical:** Gender, Vehicle Type, Education
  - **Binary:** Marital Status, Vehicle Year

## 🛠️ Technologies Used

- **Python Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- **Models Evaluated:**
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, Confusion Matrix

## 📈 Key Takeaways

- Preprocessing steps included handling missing values, encoding categorical variables, and addressing feature skewness.
- Feature importance was evaluated to help the insurance company understand the most influential variables.
- The best-performing model was selected based on a combination of performance metrics.

## 📂 File Contents

- `Final_Project_Notebook_Insurance_Claim_Prediction.ipynb` – Full notebook with code, explanations, and results
- `README.md` – Project description and insights

---

*Built for practical deployment scenarios, this notebook equips insurance teams with a clear, data-driven approach to predicting customer claim behavior.*
