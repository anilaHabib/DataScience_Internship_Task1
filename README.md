# Data Science Internship Tasks

This repository contains all my 5 tasks for the Data Science and Analytics Internship. Each task involves real-world problem solving using machine learning techniques, including data preprocessing, modeling, and evaluation.

---

## Task Summary

### Task 1: Iris Dataset Exploration
**Objective:** Explore and visualize the Iris dataset to understand feature relationships.  
**Approach:**  
- Loaded dataset using Pandas  
- Performed EDA with scatter plots, histograms, and box plots  
- Used seaborn’s pairplot for multivariable insight  

**Results & Insights:**  
- Petal length and petal width showed clear separation between species.  
- Virginica and Versicolor overlapped slightly; Setosa was clearly separable.  

---

### Task 2: Credit Risk Prediction
**Objective:** Predict whether a loan applicant is likely to default.  
**Approach:**  
- Handled missing values  
- Visualized key features (loan amount, income, education)  
- Applied Logistic Regression and Decision Tree models  
- Evaluated using accuracy and confusion matrix  

**Results & Insights:**  
- Models achieved ~86% accuracy  
- Credit history and income had strong impact on predictions  

---

### Task 3: Customer Churn Prediction
**Objective:** Identify which customers are likely to leave the bank.  
**Approach:**  
- Encoded categorical data (gender, geography)  
- Trained a Random Forest classifier  
- Evaluated with classification report  
- Handled class imbalance using class weights  

**Results & Insights:**  
- Model accuracy: ~87%  
- Recall for churned customers was low (46%)  
- Key features influencing churn: balance, tenure, is_active  

---

### Task 4: Insurance Claim Amount Prediction
**Objective:** Predict medical insurance charges based on personal data.  
**Approach:**  
- Trained a Linear Regression model  
- Visualized impact of BMI, age, and smoking status  
- Evaluated with MAE and RMSE  

**Results & Insights:**  
- Strong correlation between charges and smoking status  
- Smokers had significantly higher predicted costs  
- BMI and age also showed positive correlation with charges  

---

### Task 5: Personal Loan Acceptance Prediction
**Objective:** Predict which customers are likely to accept a personal loan offer.  
**Approach:**  
- Explored job, marital status, age  
- Used Logistic Regression and Decision Tree classifiers  
- Analyzed feature importance  

**Results & Insights:**  
- Job type and marital status were strong predictors  
- Management and single individuals showed higher acceptance rates  
- Models helped identify customer segments for targeted marketing  

---

## How to Run
- Open any `.ipynb` file in Google Colab or Jupyter Notebook  
- Follow the notebook to view code, visualizations, and analysis for each task

---

## Author
**Anila Habib**  
GitHub: [github.com/anilaHabib](https://github.com/anilaHabib)
