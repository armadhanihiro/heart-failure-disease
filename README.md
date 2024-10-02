# **Heart Failure Prediction**
This project aims to develop a predictive model for heart failure disease using machine learning techniques. Heart failure is a serious condition in which the heart is unable to pump enough blood to meet the body's needs. Early prediction of heart failure can provide critical intervention opportunities and improve patient outcomes. In this project, I leverage clinical data to predict the likelihood of heart failure.

## **Project Overview**
The dataset used in this project comes from patient's clinical test information and their heart failure disease diagnosis https://www.kaggle.com/datasets/mexwell/heart-disease-dataset/data, including features such as age, sex, chest pain type, resting blood pressure, cholesterol, etc. By applying machine learning algorithms, I aim to create a reliable model that can predict the risk of heart failure.

## **Objectives:**
- ***Data Preprocessing:*** Handle missing values, and remove outliers. <br>
- ***Exploratory Data Analysis (EDA):*** Understand the data through statistical summaries and visualizations. <br>
- ***Model Building:*** Implement multiple machine learning models (Decision Tree, Random Forest without Hyperparameter Tuning, and Random Forest with Hyperparameter Tuning) to classify patients at risk of heart failure. <br>
- ***Evaluation:*** Evaluate the models using precision, recall, and ROC-AUC score. <br>
- ***Conclusion:*** Provide insights on model performance and feature importance to support clinical decision-making.

## **Technologies Used:**
- Python (pandas, scikit-learn)
- Jupyter Notebook
- Matplotlib and Seaborn for data visualization
## **Results:**
- The final model achieved a high accuracy in predicting heart failure cases is Random Forest without Hyperparameter Tuning with ***Recall :*** 0.93, ***Precision :*** 0.92, and ***ROC-AUC :*** 0.96.
- The most important features influencing heart failure were age, and max heart rate.
