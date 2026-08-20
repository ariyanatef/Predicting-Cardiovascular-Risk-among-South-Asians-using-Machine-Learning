# Predicting-Cardiovascular-Risk-among-South-Asians-using-Machine-Learning

# Overview
This project focuses on using machine learning to predict cardiovascular disease risk among South Asian populations. Variables such as demographics, lifestyle habits, clinical issues, and other health-related variables will be used to develop multiple classification models in order to identify patterns and compare model accuracy to determine if machine learning is viable as a supplementary tool.


# Objectives
* Clean and preprocess cardiovascular data
* Explore relationships between different variables and cardiovascular disease risk
* Develop and compare multiple machine learning classification models
* Evaluate model performance using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
* Identify potential challenges related to class imbalance and model performance.


# Machine Learning Models Used
The models that were used are:
* Logistic Regression
* Random Forest Classifier
* Decision Tree Classifier
* Gradient Boosting Classifier
* XGBoost Classifier

# Tools and Technologies
* Python
* Google Colab
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* XGBoost

# Project Workflow
1. Data Cleaning- Missing values, inconsistent data, and potential outliers were addressed
2. Exploratory Data Analysis- Examined distributions and relationships between variables
3. Feature Selection & Preprocessing- Prepared relevant numerical and categorical variables for model training

4. Model Development- Trained & created multiple classification models
5. Model Evaluation- Compared models using performance metrics, with particular attention to the F1-score due to class imbalance.


# Key Findings
The dataset contained an imbalance between the CVD risk classes which influenced model performance. The models themselves demonstrated varying levels of predictive ability, F1-scores generally ranged from approximately 0.55-0.60, demonstrating the fact that the model had difficulties identifying both classes within an imbalanced dataset.

This project demonstrates the importance of considering multiple evaluation metrics rather than relying solely on accuracy when developing machine-learning models for health-related prediction tasks.


# Dataset
The dataset used for this project is the "Cardiovascular Disease Risk Assessment Dataset" published by Ahmed Mohamed Zaki.

Dataset Link: https://www.kaggle.com/datasets/ahmeduzaki/cardiovascular-disease-risk-assessment-dataset

# Future Improvements
* Applying additional techniques to address class imbalance
* Performing hyperparameter tuning
* Explore additional feature engineering methods
* Evaluating additional machine learning models
* Validating model performance using external datasets.
