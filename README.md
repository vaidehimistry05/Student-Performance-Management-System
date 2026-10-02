# Student Performance Management System

A Python-based Student Performance Management System designed to manage student records, analyze academic performance, visualize relationships between different performance factors, and predict student results using Machine Learning.

## Features

- Student record management
  - Add student
  - Search student
  - Update student
  - Delete student
  - Display student records
- Pass/Fail result calculation
- Grade-based analysis
- Performance statistics
- Statistical analysis
  - Mean
  - Median
  - Mode
  - Standard Deviation
  - Variance
  - Skewness
  - Kurtosis
  - 95% Confidence Interval
- Study hours and score analysis
- Attendance and score analysis
- Data visualization
- Sampling analysis
- Central Limit Theorem demonstration
- Logistic Regression for student performance prediction
- Prediction probability for new students
- Automated PDF performance report generation

## Technologies Used

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Scikit-learn
- ReportLab

## Dataset

The project uses a student performance dataset containing information such as:

- Student ID
- Student Name
- Weekly Self Study Hours
- Attendance Percentage
- Class Participation
- Total Score
- Grade
- Result

The dataset is used for statistical analysis, visualization, and machine learning.

## Machine Learning

The project uses **Logistic Regression** to predict whether a student will pass or fail.

### Features Used

- Weekly Self Study Hours
- Attendance Percentage
- Class Participation

### Target

- Pass / Fail Result

The dataset is divided into training and testing sets using an 80:20 split.

The model evaluates performance using:

- Accuracy
- Classification Report

The system can also predict the result and probability for a new student's input.

## Statistical Analysis

The system performs several statistical analyses on student performance data:

- Mean
- Median
- Mode
- Variance
- Standard Deviation
- Skewness
- Kurtosis
- Confidence Interval

It also demonstrates sampling and the Central Limit Theorem using multiple random samples.

## Data Visualization

The project generates visualizations to understand relationships in the dataset, including:

- Study Hours vs Total Score
- Attendance vs Total Score
- Grade Distribution
- Pass/Fail Distribution
- Other performance-related analysis

## PDF Report Generation

The system can generate an individual student performance report in PDF format using **ReportLab**.

The report can contain the student's academic information and performance details.

## Project Structure

```text
Student-Performance-Management-System/
│
├── student_performance.py
├── student_performance.csv
├── README.md
└── requirements.txt
