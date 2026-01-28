**CodeAlpha Heart Disease Detection**

**Project Description**



This project focuses on detecting heart disease using patient medical data.

It is a binary classification problem where the model predicts whether a person has heart disease or not.



The project is implemented in a Jupyter Notebook and completed as part of the CodeAlpha Machine Learning Internship (Task 4).



**Problem Statement**



Heart disease is one of the leading causes of death worldwide. Early detection using medical data can help doctors make better decisions.

The goal of this project is to build a machine learning model that predicts the presence of heart disease based on clinical attributes.



**Dataset Information**



**Dataset used**

Heart Disease Dataset from Kaggle

**Uploader:** johnsmith88



The dataset contains medical features such as:

• Age

• Sex

• Chest pain type

• Resting blood pressure

• Cholesterol

• Fasting blood sugar

• ECG results

• Heart rate

• Exercise induced angina



Target column

target

0 means no heart disease

1 means heart disease present



**Tools and Libraries Used**



* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit learn
* Imbalanced learn



**Project Workflow**

1\. **Dataset Loading**



The dataset is downloaded using kagglehub and loaded into a Pandas DataFrame.



2\. **Data Exploration**



Basic inspection is performed to understand:

• Data shape

• Column types

• Statistical summary



3\. **Data Preprocessing**



Categorical features are encoded using Label Encoding.

The dataset does not contain missing values, so no imputation was required.



4\. **Train Test Split**



The dataset is split into training and testing sets to ensure unbiased evaluation.



5\. **Handling Class Imbalance**



The target variable is imbalanced.

SMOTE is applied only on the training data to balance the classes and avoid data leakage.



6\. **Model Training**



A Random Forest classifier is trained on the balanced training dataset to capture complex patterns.



7\. **Model Evaluation**



The trained model is evaluated using multiple performance metrics and a confusion matrix.



**Model Evaluation**



The model is evaluated using the following metrics:



* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix



Recall is given high importance because missing a heart disease case can be critical.



The confusion matrix is used to clearly analyze true positives, true negatives, false positives, and false negatives.



**Results Summary**



The final model shows balanced and realistic performance across both classes.

The evaluation results confirm that the model is not biased toward one class.

No data leakage is present in the pipeline, making the results trustworthy.





**How to Run the Project**



* Clone the repository
* Install required Python libraries
* Open the notebook
* Run cells step by step
* Ensure that kagglehub and imbalanced learn are installed before execution.



**Internship Information**



This project is completed under the CodeAlpha Machine Learning Internship.



Task completed

Task 4 Disease Prediction from Medical Data



**Author**



Muhammad Sadeem Choudhary

Machine Learning Intern

Riphah University

