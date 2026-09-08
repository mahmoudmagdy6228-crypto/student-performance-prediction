# Student Performance Prediction

## Project Overview

This project analyzes student performance data and uses Data Science and Machine Learning techniques to understand the factors related to students' final scores and predict their outcomes.

The project follows a complete Data Science workflow, starting from data inspection and cleaning, followed by exploratory data analysis and visualization, and finally applying Machine Learning models.

## Objectives

* Explore student performance data.
* Identify and handle missing values.
* Detect and remove duplicate records.
* Analyze relationships between study habits, attendance, previous scores, and final scores.
* Predict students' final scores using Linear Regression.
* Predict Pass/Fail outcomes using classification models.
* Compare the performance of different Machine Learning models.

## Dataset

The dataset contains student information with the following features:

* `Student_ID` — Student identifier
* `Study_Hours` — Number of study hours
* `Attendance` — Attendance percentage
* `Previous_Score` — Previous academic score
* `Final_Score` — Final academic score

The dataset is a small synthetic dataset created for educational purposes and includes missing values and duplicate records to demonstrate data-cleaning techniques.

## Data Science Workflow

### 1. Data Inspection

The dataset is inspected using Pandas to understand its structure, dimensions, data types, descriptive statistics, missing values, and duplicate records.

### 2. Data Cleaning

Missing numerical values are handled using the median, and duplicate rows are removed. The cleaned dataset is then verified to ensure that no missing or duplicate records remain.

### 3. Exploratory Data Analysis

The project explores:

* Final score distribution
* Study Hours vs Final Score
* Attendance vs Final Score
* Previous Score vs Final Score
* Correlations between numerical features

### 4. Machine Learning

Two types of Machine Learning tasks are performed:

**Regression**

* Linear Regression is used to predict the exact Final Score.
* Evaluation metrics include MAE, RMSE, and R².

**Classification**

* Students are classified as Pass or Fail based on their Final Score.
* Logistic Regression and Decision Tree Classifier are trained and compared.
* Accuracy, classification reports, and a confusion matrix are used for evaluation.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Project Structure

```text
student-performance-prediction/
│
├── mini_project.ipynb
└── README.md
```

## Results

The project demonstrates how student study hours, attendance, and previous performance can be analyzed and used as input features for Machine Learning models.

Since the dataset is small and synthetic, the model results are mainly intended to demonstrate the Data Science workflow rather than provide conclusions about real-world student performance.

## Future Improvements

* Use a larger real-world dataset.
* Add more relevant student-related features.
* Apply cross-validation.
* Improve the preprocessing pipeline.
* Compare additional Machine Learning models.

## Author

Mahmoud Magdy
