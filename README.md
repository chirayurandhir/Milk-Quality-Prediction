# Milk Quality Prediction: A Multiclass Classification Approach

This project focuses on predicting the quality of milk using machine learning models. By analyzing various attributes of milk such as **pH**, **temperature**, **odor**, and more, this project builds a multiclass classification model to categorize milk quality into **high**, **medium**, and **low** classes.

## Problem Statement
Milk quality is essential for consumer safety and satisfaction. This project aims to develop a machine learning model to predict the quality of milk based on multiple parameters, facilitating early detection of potential issues and optimizing production processes.

## Objective
The primary objective is to create a robust model capable of accurately classifying milk quality into three categories: **high**, **medium**, and **low**.

## Dataset
The dataset includes the following milk attributes:
- **pH**
- **Temperature**
- **Taste**
- **Odor**
- **Fat content**
- **Turbidity**
- **Color**
- **Grade**

## Workflow
1. **Exploratory Data Analysis (EDA):**
   - Data Overview: Basic statistics, handling missing values, and identifying data types.
   - Univariate and Bivariate Analysis: Understanding individual features and their relationships using visualizations such as histograms, scatter plots, and correlation matrices.
   
2. **Data Preprocessing:**
   - **Missing Value Imputation:** Filling missing values using mean, median, or mode imputation.
   - **Outlier Detection:** Addressing outliers using box plots and z-scores.
   - **Feature Scaling:** Normalizing or standardizing features for optimal model performance.

3. **Model Selection:**
   - **Decision Tree:** A simple, interpretable model using rules to classify data points.
   - **Random Forest:** An ensemble method combining multiple decision trees to improve accuracy and reduce overfitting.

## Results
The models achieved the following accuracy:
- **Decision Tree:** 87.73% accuracy
- **Random Forest:** 86.79% accuracy

## Conclusion and Future Work
- The developed models successfully predict milk quality with high accuracy.
- Future work could include integrating additional data sources such as sensor data or weather patterns to further enhance model performance.
- Deploying the model in real-world dairy processing settings could provide actionable insights for optimizing milk production processes.
