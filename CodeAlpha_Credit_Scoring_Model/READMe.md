**CodeAlpha Credit Scoring Model**

**Project Overview**



This project predicts whether an individual is creditworthy based on past financial data.

It is a binary classification machine learning project completed as part of the CodeAlpha Machine Learning Internship.



The model helps identify whether a person is likely to repay a loan or not.



**Objective**



The main objective of this project is to build a machine learning model that can classify individuals as creditworthy or not creditworthy using historical financial features.



**Dataset**



The dataset used in this project is the Credit Scoring Dataset from Kaggle.



**Source**

Credit Scoring Dataset Creditworthiness Prediction by junaid512



The dataset contains financial and personal information such as income, debts, payment behavior, and other related features.



Target column

Creditworthiness

* 1 means creditworthy
* 0 means not creditworthy



**Technologies Used**



* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit learn
* Imbalanced learn



**Project Workflow**

**1. Dataset Loading**



The dataset is downloaded using kagglehub and loaded into a Pandas DataFrame.



**2. Data Understanding**



The structure, column types, and basic statistics of the dataset are analyzed.



**3. Data Preprocessing**



Categorical columns are encoded using Label Encoding.

The dataset does not contain missing values, so no imputation was required.



**4. Train Test Split**



The dataset is split into training and testing sets to ensure fair evaluation and avoid data leakage.



**5. Handling Class Imbalance**



The target variable was imbalanced.

SMOTE was applied only on the training data to balance the classes correctly.



**6. Model Training**



A Random Forest classifier was trained on the balanced training dataset to learn patterns effectively.



**7. Model Evaluation**



The model performance was evaluated using multiple metrics instead of accuracy alone.



**Model Evaluation Metrics**



The following evaluation metrics were used:



* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix



Recall and F1 score were given importance because credit risk prediction requires identifying risky cases correctly.



**Results**



The trained model shows balanced performance across both classes.

The confusion matrix confirms that the model predicts both creditworthy and non creditworthy cases effectively.

The evaluation results are realistic and reliable.



**How to Run the Project**



* Clone the repository
* Install required Python libraries
* Run the notebook step by step
* Make sure kagglehub and imbalanced learn are installed before running the project.



**Internship Information**



This project is completed as part of the CodeAlpha Machine Learning Internship.



Completed task

Task 1 Credit Scoring Model



**Author**



Muhammad Sadeem Choudhary

Machine Learning Intern at CodeAlpha


