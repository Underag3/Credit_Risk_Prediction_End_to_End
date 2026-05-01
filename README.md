# Credit Risk Assessment and Lending Policy Simulation

## 📌 Overview
This project develops an end-to-end credit risk prediction system using machine learning to support data-driven lending decisions. The model identifies high-risk borrowers and enables financial institutions to balance loan approval rates with default risk exposure.

The solution integrates predictive modeling, threshold optimization, policy simulation, and explainability to provide a transparent and practical decision-support system.

---

## 🎯 Objectives
- Predict borrower default risk (Good vs Bad loans)
- Optimize decision thresholds beyond default classification (0.5)
- Simulate lending policies under different risk strategies
- Provide explainable insights into model predictions

---

## 📊 Dataset
The dataset consists of historical loan records containing borrower financial information and loan outcomes.

**Key Characteristics:**
- Large-scale loan dataset
- Mix of numerical and categorical features
- Target variable derived from loan status (Good vs Bad)

---

## ⚙️ Methodology

### 1. Data Preparation
- Missing value handling
- Feature encoding (One-Hot Encoding)
- Target variable construction
- Data leakage prevention
- Train-test split

---

### 2. Modeling
Multiple algorithms were evaluated:

- Logistic Regression (baseline)
- XGBoost (final model)

**Why XGBoost?**
- Handles nonlinear relationships effectively
- Robust to feature interactions
- Strong performance in classification tasks

---

### 3. Threshold Optimization
Instead of using a fixed threshold (0.5), multiple thresholds were evaluated to:

- Control approval rate
- Reduce default risk
- Align model output with business objectives

---

### 4. Risk Policy Simulation
Model predictions were translated into real-world lending decisions:

- **Risk Detection Policy** → prioritize catching risky borrowers
- **Conservative Policy** → prioritize low default rate

This allows simulation of business trade-offs before deployment.

---

### 5. Model Explainability
To ensure transparency:

- Feature Importance analysis (global)
- SHAP (SHapley Additive Explanations):
  - Global interpretation (summary plot)
  - Local interpretation (individual prediction)

Key risk drivers identified:
- Debt-to-Income Ratio (DTI)
- Credit Utilization
- Interest Rate
- Loan Grade

---

## 📈 Key Results
- XGBoost outperformed baseline models in risk classification
- Threshold tuning significantly improved business alignment
- Policy simulation demonstrated clear trade-offs between:
  - Approval rate
  - Default risk exposure
- Model explanations confirmed alignment with financial risk principles

---

## 💼 Business Impact
- Enables data-driven loan approval decisions
- Reduces exposure to high-risk borrowers
- Provides flexible lending strategy via threshold adjustment
- Improves transparency and trust through explainable AI

---

## 🧠 Project Structure
# Credit Risk Assessment and Lending Policy Simulation

## 📌 Overview
This project develops an end-to-end credit risk prediction system using machine learning to support data-driven lending decisions. The model identifies high-risk borrowers and enables financial institutions to balance loan approval rates with default risk exposure.

The solution integrates predictive modeling, threshold optimization, policy simulation, and explainability to provide a transparent and practical decision-support system.

---

## 🎯 Objectives
- Predict borrower default risk (Good vs Bad loans)
- Optimize decision thresholds beyond default classification (0.5)
- Simulate lending policies under different risk strategies
- Provide explainable insights into model predictions

---

## 📊 Dataset
The dataset consists of historical loan records containing borrower financial information and loan outcomes.

**Key Characteristics:**
- Large-scale loan dataset
- Mix of numerical and categorical features
- Target variable derived from loan status (Good vs Bad)

---

## ⚙️ Methodology

### 1. Data Preparation
- Missing value handling
- Feature encoding (One-Hot Encoding)
- Target variable construction
- Data leakage prevention
- Train-test split

---

### 2. Modeling
Multiple algorithms were evaluated:

- Logistic Regression (baseline)
- XGBoost (final model)

**Why XGBoost?**
- Handles nonlinear relationships effectively
- Robust to feature interactions
- Strong performance in classification tasks

---

### 3. Threshold Optimization
Instead of using a fixed threshold (0.5), multiple thresholds were evaluated to:

- Control approval rate
- Reduce default risk
- Align model output with business objectives

---

### 4. Risk Policy Simulation
Model predictions were translated into real-world lending decisions:

- **Risk Detection Policy** → prioritize catching risky borrowers
- **Conservative Policy** → prioritize low default rate

This allows simulation of business trade-offs before deployment.

---

### 5. Model Explainability
To ensure transparency:

- Feature Importance analysis (global)
- SHAP (SHapley Additive Explanations):
  - Global interpretation (summary plot)
  - Local interpretation (individual prediction)

Key risk drivers identified:
- Debt-to-Income Ratio (DTI)
- Credit Utilization
- Interest Rate
- Loan Grade

---

## 📈 Key Results
- XGBoost outperformed baseline models in risk classification
- Threshold tuning significantly improved business alignment
- Policy simulation demonstrated clear trade-offs between:
  - Approval rate
  - Default risk exposure
- Model explanations confirmed alignment with financial risk principles

---

## 💼 Business Impact
- Enables data-driven loan approval decisions
- Reduces exposure to high-risk borrowers
- Provides flexible lending strategy via threshold adjustment
- Improves transparency and trust through explainable AI

---

## 🧠 Project Structure
0 Setup & Data Loading
1 Business Understanding
2 Methodology
3 Data Understanding
4 Data Quality Assessment
5 Exploratory Data Analysis
6 Data Preparation
7 Modeling
8 Threshold Optimization
9 Risk Policy Simulation
10 Model Explainability
11 Conclusion

---

## 🚀 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- SHAP
- Matplotlib, Seaborn

---

## 📌 Future Improvements
- Hyperparameter tuning (Grid/Optuna)
- Model monitoring and drift detection
- Integration with real-time scoring systems
- Inclusion of macroeconomic features

---

## 👤 Author
Mohammad Tyas Subianto
Data Scientist Project Based Intern – ID/X Partners X Rakamin Academy

---
