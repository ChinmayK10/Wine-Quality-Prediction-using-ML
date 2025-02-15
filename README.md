# Wine quality prediction using Machine Learning

This repository contains a Jupyter Notebook for predicting wine quality using machine learning techniques. The project explores data preprocessing, feature selection, model training, and evaluation to determine the key factors influencing wine quality.

In this project, I utilized Kaggle’s Red Wine Quality dataset to develop multiple classification models aimed at predicting whether a given red wine qualifies as “good quality.” The dataset assigns each wine a quality score ranging from 0 to 10. For this analysis, I transformed the target variable into a binary classification, categorizing wines as either “good quality” (scores of 7 or above) or otherwise (scores below 7). The quality assessment is based on 11 key physicochemical attributes.

# Objectives
To systematically evaluate different classification algorithms to identify the one that delivers the highest predictive accuracy for wine quality. Additionally, to analyze and determine the most influential features that contribute to distinguishing high-quality wine from lower-quality counterparts, thereby gaining insights into the key physicochemical properties that impact wine quality.

## Dataset
The dataset used in this project consists of physicochemical properties of wine samples, including:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (Target variable)

## Machine Learning Approach
This project utilizes machine learning algorithms to predict wine quality based on its physicochemical properties. The following steps are performed:

1. **Data Preprocessing**
   - Handling missing values (if any)
   - Normalizing or standardizing numerical features
   - Splitting data into training and testing sets

2. **Feature Selection**
   - Analyzing correlation between features and target variable
   - Selecting the most significant predictors

3. **Model Training & Evaluation**
   - Training multiple machine learning models including:
     - Logistic Regression
     - Decision Trees
     - Random Forest
     - Support Vector Machines (SVM)
     - Gradient Boosting
   - Evaluating models based on accuracy, precision, recall, and F1-score
   - Fine-tuning hyperparameters using cross-validation

4. **Results Visualization**
   - Plotting feature importance
   - Confusion matrices for model performance evaluation
   - ROC curves for classification analysis

