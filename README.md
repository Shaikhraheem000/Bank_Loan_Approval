# Credit-Wise: Bank Loan Approval Prediction

##  Project Overview
**Credit-Wise** is a machine learning project focused on predicting **bank loan approval** based on applicant financial and personal information.  
The goal is to help financial institutions make faster, data-driven, and more consistent loan approval decisions.

This project explores data preprocessing, feature engineering, and multiple classification algorithms to identify the best-performing model.

---

##  Dataset
- **File:** `loan_approval_data.csv`
- **Target Variable:** Loan approval status (Approved / Not Approved)
- **Features include:**
  - Applicant income
  - Loan amount
  - Credit history
  - Employment details
  - Other demographic and financial attributes

---

##  Workflow
The project follows a standard machine learning pipeline:

1. **Data Loading & Exploration**
   - Shape, data types, summary statistics
   - Initial understanding of feature distributions

2. **Handling Missing Values**
   - Used `SimpleImputer` for numerical and categorical features

3. **Feature Engineering**
   - Encoding categorical variables
   - Scaling numerical features

4. **Train-Test Split**
   - Dataset split into training and testing sets

5. **Model Building**
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Naive Bayes (GaussianNB)

6. **Model Evaluation**
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - Confusion Matrix

---

##  Models Used

| Model | Description |
|------|-------------|
| Logistic Regression | Baseline model, interpretable and efficient |
| K-Nearest Neighbors | Distance-based classification |
| Naive Bayes | Probabilistic classifier assuming feature independence |

---

##  Results
- All models performed comparably after feature engineering
- **Logistic Regression** emerged as the most stable and reliable baseline model
- Feature engineering did not significantly outperform the baseline model

---

##  Libraries & Tools
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

