# Loan Repayment Prediction for NBFC

This project aims to develop a classification model to predict loan repayment behavior for a Non-Banking Financial Company (NBFC). The goal is to identify potential defaulters and non-defaulters based on historical loan data, thus enhancing the risk assessment and loan approval process.

---

## **Project Overview**

The NBFC is in the process of creating a model to predict loan repayment behavior. This involves classifying loan applicants into defaulters (1) and non-defaulters (0), which will help in assessing the risk involved in each loan application.

### **Project Goals:**

- **Exploratory Data Analysis (EDA):** To understand the dataset, identify trends, and uncover any patterns in the data.
- **Model Development:** Implement at least two machine learning models to classify loan repayment behavior.
- **Model Selection:** Compare models based on evaluation metrics and select the best-performing model.
- **Hyperparameter Tuning:** If necessary, perform hyperparameter tuning to improve the model’s performance.

---

## **Data Overview**

The data is divided into two main files:

1. **`train_data.xlsx` (Historic Data):**
   - Contains loan disbursement applications and their default status for the past 2+ years.
   
2. **`test_data.xlsx` (Validation Data):**
   - Contains loan disbursement applications and their default status for the past 3 months.

### **Columns in the dataset:**
- `customer_id`: Unique ID for each customer.
- `transaction_date`: Date of the loan transaction.
- `sub_grade`: Customer classification based on various factors like geography, income, and age.
- `term`: Total loan tenure.
- `home_ownership`: The applicant's home ownership status.
- `cibil_score`: Credit score of the applicant.
- `total_no_of_acc`: Total number of bank accounts held by the applicant.
- `annual_inc`: Annual income of the applicant.
- `int_rate`: Interest rate charged by the NBFC.
- `purpose`: The purpose for taking the loan.
- `loan_amnt`: Total loan amount.
- `application_type`: Type of applicant.
- `installment`: Amount of installment.
- `verification_status`: Applicant verification status.
- `account_bal`: Total account balance as per the previous month.
- `emp_length`: Number of years of employment experience.
- `loan_status`: Loan status (1: default, 0: non-default).

---

## **Project Files**

### **1. `eda.ipynb`**  
- **Purpose:** This Jupyter notebook contains the Exploratory Data Analysis (EDA) process. It includes:
  - Data cleaning and transformation.
  - Visualizations and statistical summaries.
  - Identification of trends and patterns in the dataset.

### **2. `model_.py`**  
- **Purpose:** This Python script contains the model training pipeline. It includes:
  - Class-based structure for loading, preprocessing, training, testing, and predicting with machine learning models.
  - Implementation of at least two machine learning models (e.g., Logistic Regression and Random Forest).
  
### **3. `model_selection.ipynb`**  
- **Purpose:** This Jupyter notebook handles model selection, including:
  - Training and evaluating multiple models.
  - Hyperparameter tuning (if required).
  - Comparison of evaluation metrics such as accuracy, precision, recall, and F1-score.
  - Selection of the best-performing model based on these metrics.

---


