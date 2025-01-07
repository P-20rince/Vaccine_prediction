# Vaccine/Medicine Probability Prediction Model
## Overview
This project leverages machine learning techniques to predict the probabilities of individuals receiving one type of medicine, both types, or no medicine/vaccine at all. The model aims to assist in decision-making for vaccine distribution and medical resource allocation, addressing real-world challenges in public health.    

## Motivation
Efficient vaccine distribution is critical in public health, especially during pandemics or large-scale vaccination drives. This project aims to create a predictive system that informs stakeholders about the likelihood of individuals falling into one of three categories:    

  1. Received one type of medicine.
  2. Received both types of medicine.
  3. Did not receive any medicine.

## Objectives
  - Preprocess and analyze datasets to extract meaningful features and eliminate inconsistencies.    
  - Develop a machine learning model to predict the probabilities for each category.      
  - Visualize prediction probabilities and class distributions to gain actionable insights.    
  - Evaluate and fine-tune the model for optimal performance.    


## Dataset

### Description:
  - Contains anonymized data on individuals, their demographic details, medical history, and vaccine/medicine distribution status.    
### Features:    
   -  Demographics (e.g., age, gender, location)      
   -  Medical history (e.g., chronic illnesses, prior vaccinations)    
   -  Distribution records (e.g., received medicine type A, type B, or none)    
### Approach
  1. Data Preprocessing:
      -  Cleaned and transformed raw data using Pandas to ensure consistency and reliability.
      -  Handled missing values, normalized features, and encoded categorical variables.
  2. Exploratory Data Analysis (EDA):
     -  Analyzed distributions and correlations between key variables using Seaborn and Matplotlib.
  3. Model Development:
     -  Trained classification models (e.g., Logistic Regression, Random Forest, XGBoost) to predict probabilities.
     -  Evaluated performance using metrics like accuracy, precision, recall, and F1 score.
  4. Hyperparameter Tuning:
     -  Used GridSearchCV and RandomizedSearchCV to optimize model parameters for improved predictions.
  5. Visualization:
    -  Plotted prediction probabilities and category distributions for actionable insights.

## Key Results
  1. Achieved an accuracy of X% and an F1 score of Y% for the best-performing model.    
  2. Visualized prediction probabilities, enabling stakeholders to understand the likelihood of each category.      
  3. Provided recommendations for optimizing vaccine distribution strategies based on the results.    
## Technologies and Tools
Languages: Python  
Libraries: scikit-learn, Pandas, NumPy, Matplotlib, Seaborn  
Tools: Jupyter Notebook  
