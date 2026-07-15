#  Loan Approval Prediction using Support Vector Machine (SVM)

A Machine Learning project that predicts whether a loan application will be **Approved** or **Rejected** based on an applicant's demographic, financial, and credit-related information.

The project demonstrates the complete Machine Learning workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction using a **Support Vector Machine (SVM)** classifier.

---

##  Project Overview

Financial institutions receive thousands of loan applications every day. Evaluating every application manually is time-consuming and prone to human bias.

This project automates the loan approval process by building an SVM classification model capable of predicting loan approval decisions based on historical applicant data.

---

##  Objectives

- Understand the loan approval dataset
- Perform data cleaning and preprocessing
- Handle missing values
- Encode categorical variables
- Train an SVM classifier
- Evaluate model performance
- Predict loan approval for new applicants

---

##  Dataset Information

The dataset contains customer information such as:

- Gender
- Marital Status
- Dependents
- Education
- Self Employment
- Applicant Income
- Co-applicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area

**Target Variable**

- Loan Status
  - Approved
  - Rejected

---

##  Machine Learning Workflow

1. Data Loading
2. Data Cleaning
3. Handling Missing Values
4. Exploratory Data Analysis (EDA)
5. Feature Encoding
6. Train-Test Split
7. Feature Scaling
8. Model Training using Support Vector Machine (SVM)
9. Model Evaluation
10. Prediction

---

##  Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

##  Project Structure

```
Loan_Approval_Prediction_SVM/
│
├── Loan_Approval_Prediction.ipynb
├── loan.csv
├── README.md
└── requirements.txt
```

---

##  Installation

Clone the repository

```bash
git clone https://github.com/ankitpanchal0001/Loan_Approval_Prediction_SVM.git
```

Move into the project directory

```bash
cd Loan_Approval_Prediction_SVM
```

Install the required libraries

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

##  Model Used

### Support Vector Machine (SVM)

Support Vector Machine is a supervised machine learning algorithm widely used for classification tasks. It identifies the optimal decision boundary (hyperplane) that best separates different classes while maximizing the margin between them.

---

##  Model Evaluation

The model was evaluated using standard classification metrics such as:

- Accuracy
- Confusion Matrix
- Classification Report

---

##  Future Improvements

- Hyperparameter tuning using GridSearchCV
- Compare SVM with Random Forest, XGBoost, and Logistic Regression
- Build a Streamlit web application
- Deploy the model on Render or Hugging Face Spaces
- Explain predictions using SHAP values

---

##  Learning Outcomes

Through this project, I gained practical experience in:

- Data preprocessing
- Feature engineering
- Exploratory Data Analysis
- Classification problems
- Support Vector Machine (SVM)
- Model evaluation
- End-to-end Machine Learning workflow

---

##  Author

**Ankit Panchal**

Aspiring AI/ML Engineer

GitHub: https://github.com/ankitpanchal0001

LinkedIn: https://www.linkedin.com/in/ankitpanchal0001/

---

##  If you found this project useful

Please consider giving this repository a **Star ⭐**.
