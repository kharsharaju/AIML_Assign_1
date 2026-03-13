# AIML Assignment 1 - Student Exam Score Prediction

## Problem Statement
The objective of this assignment is to build a simple Machine Learning model using Python to predict student exam scores based on study hours and attendance. The assignment demonstrates the complete ML workflow including dataset creation, data exploration, visualization, model training, evaluation, and feature experimentation.

## Dataset Description
A custom dataset was created using a Pandas DataFrame with 15 rows. The dataset includes the following features:

- **Hours_Studied** – Number of hours a student studied
- **Attendance** – Student attendance percentage
- **Exam_Score** – Final exam score (target variable)

An additional feature called **Study_Efficiency** was later created for experimentation.

## Data Exploration
Basic data analysis was performed including:
- Viewing first and last rows
- Checking dataset shape
- Inspecting data types
- Checking for missing values

## Data Visualization
Three types of visualizations were created to understand the dataset:

- Scatter Plot (Hours Studied vs Exam Score)
- Histogram (Distribution of Exam Scores)
- Boxplot (Exam Score spread)

These visualizations help identify relationships and distribution patterns.

## Model Used
A **Linear Regression** model from the Scikit-Learn library was used to predict exam scores.

Steps followed:
1. Split dataset into training and testing sets
2. Train the Linear Regression model
3. Make predictions
4. Evaluate model performance

## Evaluation Metrics
Two evaluation metrics were used:

- **MAE (Mean Absolute Error)** – Measures the average prediction error
- **R² Score** – Indicates how well the model explains the variance in the data

## Feature Experiment
Two experiments were performed:

1. **Removing Attendance feature**
   - Performance slightly decreased.

2. **Adding Study Efficiency feature**
   - Performance slightly improved.

This shows that attendance contributes to predicting exam performance.

## Overfitting Check
The model was trained on the full dataset without a train-test split. This produced a higher R² score but may not reflect real-world performance. This demonstrates the concept of **overfitting**, where a model memorizes training data rather than learning general patterns.

## Conclusion
This assignment demonstrates the complete machine learning pipeline using Python. Study hours and attendance both influence exam scores, and feature engineering can slightly improve model performance.

---

**Author:**  
K Harshavardhan  
AI/ML Intern
