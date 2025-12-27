# Data Preprocessing, Visualization, and Supervised Learning

## Overview
This project demonstrates a complete machine learning workflow using a structured dataset. 
It includes data preprocessing, exploratory data analysis (EDA), visualization, and the 
implementation of a supervised learning algorithm for classification.

---

## Dataset
The dataset contains numerical features related to medical measurements and a binary target
variable named `Outcome`. The goal is to predict the target variable based on the input features.

---

## Project Workflow

### 1. Data Preprocessing
The following preprocessing steps were performed:
- Identified invalid zero values in selected columns
- Replaced zero values with the median of each feature
- Separated features and target variable
- Applied feature scaling using `StandardScaler`

---

### 2. Exploratory Data Analysis (EDA)
EDA was conducted to understand the data distribution and feature relationships:
- Histograms to analyze feature distributions
- Count plot to visualize target variable distribution
- Correlation heatmap to observe feature relationships
- Boxplots for outlier detection
- Boxplots grouped by target variable for comparison

---

### 3. Supervised Learning
- Algorithm used: **Logistic Regression**
- The dataset was split into training (80%) and testing (20%) sets
- The model was trained on scaled features

---

### 4. Model Evaluation
Model performance was evaluated using:
- Accuracy score
- Confusion matrix
- ROC curve and AUC score

---

## Results and Insights
- Logistic Regression achieved good classification performance
- Features such as glucose level and BMI had a strong influence on predictions
- Data preprocessing and scaling improved model performance

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Conclusion
In this project, Logistic Regression was trained and evaluated using preprocessed and scaled data to understand how well the model can classify the outcome. The evaluation results show that the model is able to learn patterns from the data and distinguish between diabetic and non-diabetic cases. This workflow demonstrates the use of supervised learning for classification problems.

---
