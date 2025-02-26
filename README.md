# student-grade-prediction

This repository contains a machine learning project for predicting student grades and total scores.

📌 Project Overview

The goal of this project is to analyze student performance based on various factors and build predictive models for:
Grade Classification: Predicting student grades (A, B, C, D, F).

Score Regression: Predicting the total score of a student.
The dataset used in this project includes information such as study hours, attendance, midterm scores, and final scores.

📂 Dataset

The dataset is available in the repository:
metadata.xlsx → Contains student performance data used for model training.
students-grading-dataset.csv → Contains student performance dataset via csv

🔧 Model Training

We use Random Forest for both classification and regression tasks:

Classification Model (Random Forest)

Achieved 100% accuracy in predicting student grades.

Regression Model (Random Forest)
Achieved Mean Absolute Error (MAE) of 12.89 for total score prediction.



📊 Results

Strong correlation between Final Score, Midterm Score, and Total Score.
Weak correlation between Attendance, Study Hours, and Total Score.
Grade distribution: Majority of students received A, but a notable number received F.


🚀 How to Run the Project

1. Clone this repository:
git clone https://github.com/azozing/student-grade-prediction.git

2. Install dependencies:
pip install -r requirements.txt

4. Run the notebook or script to train the model:
python train_model.py


📌 Repository Structure

📂 student-grade-prediction  
├── 📄 README.md  
├── 📄 metadata.xlsx  # Dataset  
├── 📄 train_model.py  # Model training script  
├── 📄 requirements.txt  # Dependencies  
└── 📄 Prediction_Assignment_Writeup.pdf  # Report

📌 Future Improvements
- Improve the regression model with advanced feature engineering.
- Experiment with other machine learning algorithms for better accuracy.
- Deploy the model using a web-based interface for easier access.

📬 Contact
If you have any questions, feel free to reach out:
✉️ malfarazoo@gmail.com

