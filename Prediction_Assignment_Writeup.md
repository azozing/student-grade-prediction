
# Prediction Assignment Writeup

## 1. Introduction
This project aims to predict student grades and total scores based on various academic and lifestyle factors using machine learning models.

## 2. Data Preprocessing
- Removed irrelevant columns (e.g., Student ID, Name, Email).
- Handled missing values (median for numeric, mode for categorical).
- Encoded categorical variables using One-Hot Encoding.
- Scaled numeric features using StandardScaler.

## 3. Exploratory Data Analysis
- Strong correlation between Final_Score, Midterm_Score, and Total_Score.
- Attendance and Study Hours showed weak correlation with Total_Score.
- Grade distribution: Majority of students achieved an A, with a notable number receiving F.

## 4. Model Training
- **Classification Model (Random Forest) for Grade Prediction**
  - Achieved **100% accuracy** in predicting student grades.
- **Regression Model (Random Forest) for Total Score Prediction**
  - Achieved **Mean Absolute Error (MAE) of 12.89**.

## 5. Conclusion
- The classification model performed exceptionally well, likely due to clear patterns in grading.
- The regression model showed reasonable accuracy but could be improved with feature engineering.

## 6. Repository
You can find the dataset and code in this GitHub repository [https://github.com/azozing/student-grade-prediction](https://github.com/azozing/student-grade-prediction).
