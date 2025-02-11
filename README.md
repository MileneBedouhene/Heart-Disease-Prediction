# Heart Disease Prediction

This repository contains a machine learning model for predicting heart disease using the Cardiovascular Disease dataset from Kaggle.

## Dataset
The dataset used for this project can be found here: [Cardiovascular Disease Dataset](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset). It includes medical records of patients with various health attributes that can help in predicting the presence of heart disease.

## Features
The dataset consists of the following key features:
- **Age** (in years)
- **Gender** (1: Female, 2: Male)
- **Height** (cm)
- **Weight** (kg)
- **Blood Pressure** (Systolic & Diastolic)
- **Cholesterol Levels** (Normal, Above Normal, Well Above Normal)
- **Glucose Levels** (Normal, Above Normal, Well Above Normal)
- **Smoking Status**
- **Alcohol Consumption**
- **Physical Activity**
- **Cardiovascular Disease** (Target Variable: 0 - No, 1 - Yes)

## Model and Approach
The model is built using the following steps:
1. **Data Preprocessing**: Handling missing values, normalizing numerical features, and encoding categorical variables.
2. **Exploratory Data Analysis (EDA)**: Visualizing feature distributions and correlations.
3. **Feature Engineering**: Selecting the most relevant features to improve model performance.
4. **Model Training**: Implementing the Random Forest algorithm for classification.
5. **Evaluation**: Using metrics like accuracy, precision, recall, and ROC-AUC score to assess model performance.

## Results
The best-performing model achieved an accuracy of **89%** with a ROC-AUC score of **Y**.

## Future Improvements
- Hyperparameter tuning for better model optimization.
- Implementation of deep learning techniques.
- Integration of a web application for real-time predictions.


## Acknowledgments
- Kaggle for providing the dataset.
- Open-source ML libraries such as Scikit-learn and Pandas.


