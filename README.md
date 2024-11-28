# Heart Disease

**Analysis of cardiovascular health indicators using classification algorithms for patient diagnosis.**

## Introduction

The dataset under examination is a classic resource used in medical diagnostics, particularly for predicting heart disease. Originating from a collection of databases compiled in 1988, this dataset includes records from Cleveland, Hungary, Switzerland, and Long Beach V. It features a total of 76 attributes, with 14 key attributes commonly used for analysis and prediction. The goal is to utilize various machine learning and statistical techniques to classify patients based on their attributes and assess the effectiveness of different methods in predicting heart disease.

## Usage

This dataset can be utilized for various tasks in cardiovascular health analysis, including:

1. *Predictive Modeling*: 
   - Train classification algorithms to predict the presence of heart disease based on patient attributes such as age, gender, chest pain type, and other health indicators.

2. *Exploratory Data Analysis (EDA)*: 
   - Analyze and visualize the relationships between different features, such as cholesterol levels and resting blood pressure, and their correlation with heart disease.

3. *Performance Evaluation*:
   - Evaluate model effectiveness using metrics such as accuracy, precision, recall, and ROC-AUC score to understand how well the model predicts heart disease.
  

## Libraries Used

1. **NumPy:**  
   A library for numerical operations and array manipulation, commonly used for scientific and engineering calculations.

2. **Pandas:**  
   A data manipulation and analysis tool, especially for structured data, providing data structures like DataFrames.

3. **Matplotlib:**  
   A plotting library used for creating static, animated, and interactive visualizations in Python.

4. **Seaborn:**  
   A statistical data visualization library based on Matplotlib, providing a high-level interface for drawing attractive and informative graphics.

5. **Scikit-learn:**  
   A comprehensive library for data science and machine learning, offering tools for model selection, training, and evaluation.
   - **GaussianNB:** A probabilistic classifier based on Bayes' theorem, used for classification tasks.
   - **Logistic Regression:** A model used for binary classification based on logistic functions.
   - **Linear Discriminant Analysis (LDA):** A classification technique that improves class separation.
   - **Quadratic Discriminant Analysis (QDA):** A classification technique that estimates class-specific probability distributions, allowing for different variances between classes.

6. **Imbalanced-learn:**  
   A library used for handling imbalanced datasets, including techniques like SMOTE (Synthetic Minority Over-sampling Technique) to increase the number of samples in the minority class.


## Exploratory Data Analysis

**Attributes of the Dataset:**

- **age:** Age of the patient (integer)
- **sex:** Gender (1 = male, 0 = female)
- **cp:** Chest pain type (categorical)
- **trestbps:** Resting blood pressure (integer)
- **chol:** Serum cholesterol in mg/dl (integer)
- **fbs:** Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- **restecg:** Resting electrocardiographic results (categorical)
- **thalach:** Maximum heart rate achieved (integer)
- **exang:** Exercise-induced angina (1 = yes, 0 = no)
- **oldpeak:** ST depression induced by exercise (float)
- **slope:** Slope of the peak exercise ST segment (categorical)
- **ca:** Number of major vessels colored by fluoroscopy (integer)
- **thal:** Thalassemia (categorical)
- **target:** Target variable indicating the presence of heart disease (1 = disease, 0 = no disease)

## Links

- [Link to Google Colab](https://colab.research.google.com/drive/17UEhNE9lCwMhyw2fNrF8__jMWlygHwm1?usp=sharing)  
- [Link to Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)


## Credits

This file was created by:
- [Joud Ahmad Al-huthaly](https://github.com/BYXDATA)
- [Nehal Hamed Al-zahrani](https://github.com/nehal3589)
