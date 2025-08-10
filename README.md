# CodeAlpha-Credit-Scoring-Model
## 📌 Overview
This project is part of my **CodeAlpha Internship** and focuses on predicting the credit risk of customers based on historical financial data.  
We used the **German Credit Dataset** and applied **Logistic Regression** to classify customers into two categories:
- **Good Credit Risk**
- **Bad Credit Risk**

---

## 🎯 Objective
The main goal of this project is to help financial institutions make better lending decisions by predicting whether a customer is likely to repay a loan or default.

---

## 📊 Dataset
- **Name:** German Credit Dataset
- **Target Variable:** `Creditability` (1 = Good Credit, 0 = Bad Credit)
- **Features:** Age, Credit Amount, Duration, Housing, Job, and other financial indicators
- **Source:** Dataset provided during the internship

---

## 🛠 Tools & Libraries Used
- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**

---

## 📈 Model & Approach
1. **Data Preprocessing**
   - Handled categorical variables using **One-Hot Encoding**.
   - Scaled numerical features using **StandardScaler**.
   
2. **Train-Test Split**
   - 80% training data, 20% testing data.
   - Stratified sampling to maintain class balance.

3. **Model Training**
   - Applied **Logistic Regression** for binary classification.

4. **Evaluation Metrics**
   - Accuracy
   - Precision, Recall, F1-Score
   -confusion matrix
