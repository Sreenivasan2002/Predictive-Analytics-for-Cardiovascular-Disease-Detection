# Cardiovascular Disease Prediction

## Project Overview
The goal of this project is to predict the presence or absence of cardiovascular disease in a person based on several features related to demographics, health indicators, and examination results. The dataset contains both objective measurements (e.g., height, weight, blood pressure) and subjective features (e.g., smoking habits, alcohol consumption).

## Dataset
The dataset used in this project is publicly available from [Kaggle](https://www.kaggle.com/sulianova/cardiovascular-disease-dataset). It includes the following features:

- **Age**: Integer (in days)
- **Height**: Integer (in cm)
- **Weight**: Float (in kg)
- **Gender**: Categorical (1 = male, 2 = female)
- **Systolic Blood Pressure**: Integer
- **Diastolic Blood Pressure**: Integer
- **Cholesterol**: Categorical (1 = normal, 2 = above normal, 3 = well above normal)
- **Glucose**: Categorical (1 = normal, 2 = above normal, 3 = well above normal)
- **Smoking**: Binary (0 = no, 1 = yes)
- **Alcohol Intake**: Binary (0 = no, 1 = yes)
- **Physical Activity**: Binary (0 = no, 1 = yes)
- **Cardiovascular Disease**: Binary target variable (0 = no disease, 1 = disease)

## Objective
The aim is to build a predictive model that accurately classifies whether a person has cardiovascular disease based on the available features.

## Steps Followed:
1. **Problem Understanding**: Understanding the features and the problem statement.
2. **Data Import and Exploration**: Importing the dataset and performing exploratory data analysis (EDA) to understand distributions, correlations, and data quality.
3. **Data Preprocessing**: Cleaning the data by handling missing values, encoding categorical variables, and scaling numerical features.
4. **Model Building**: Applying various machine learning algorithms such as Logistic Regression, Decision Trees, Random Forest, etc., to predict cardiovascular disease.
5. **Model Evaluation**: Evaluating model performance using metrics like accuracy, precision, recall, and F1-score.

## Libraries Used:
- **Pandas**: For data manipulation.
- **NumPy**: For numerical computations.
- **Seaborn & Matplotlib**: For data visualization.
- **Scikit-Learn**: For machine learning algorithms and model evaluation.

## Usage
1. Clone this repository.
2. Install the required libraries by running: 
   ```bash
   pip install -r requirements.txt
