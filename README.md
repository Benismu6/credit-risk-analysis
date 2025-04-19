## 🏦 Credit Risk Analysis

This project predicts the likelihood of a loan applicant defaulting based on financial and demographic data. Accurate prediction helps lenders minimize risk and make better credit decisions.

### 📌 Objective:
Predict default (`SeriousDlqin2yrs`) using classification models.

---

### 📊 Key Steps:
1. **Data Cleaning**: Handled missing income and dependents, dropped invalid ages
2. **EDA**: Explored trends across age, income, debt ratio, and payment history
3. **Modeling**: Compared Logistic Regression and Random Forests
4. **Class Imbalance**: Applied `SMOTE` to improve detection of rare default cases
5. **Feature Importance**: Identified top predictors of credit risk

---

### 🤖 Final Model:
- **Model**: Random Forest + SMOTE
- **Accuracy**: 93%
- **Recall (Default)**: 30% (up from 4% baseline)
- **ROC AUC**: 0.84
- **Top Features**:
  - Number of late payments
  - Debt Ratio
  - Revolving Credit Utilization
  - Age

---

### 📁 Files:
- `notebooks/01_eda.ipynb` — EDA + cleaning
- `notebooks/02_modeling.ipynb` — modeling + evaluation
- `data/raw/credit_data.csv` — original dataset
- `README.md` — this file

---

### 🛠️ Skills Demonstrated:
- Classification modeling (LogReg, Random Forest)
- Handling imbalanced data (SMOTE)
- Feature importance interpretation
- Financial risk analysis
