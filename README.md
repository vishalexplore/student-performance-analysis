# 🎓 Student Performance Analysis & Prediction

An Exploratory Data Analysis and Machine Learning project that analyzes student academic performance and predicts final grades using Python and Scikit-learn.

## 📌 Project Overview

This project analyzes data from 397 students to understand patterns in academic performance and build a machine learning model for predicting the final grade (`G3`).

## 🎯 Objectives

- Explore student academic performance
- Analyze final grade distribution
- Study the relationship between study time and grades
- Analyze absences and academic performance
- Examine previous grades (G1 and G2)
- Build a Machine Learning model to predict final grades
- Evaluate model performance

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Kaggle

## 📊 Dataset

The dataset contains:

- **397 students**
- **33 features**
- Academic, demographic, social and school-related information

### Target Variable

`G3` — Final Grade

The final grade ranges from **0 to 20**.

## 🔎 Key Findings

- Average final grade: **10.38**
- G2 and G3 correlation: **0.905**
- G1 and G3 correlation: **0.803**
- Absences and G3 correlation: approximately **0.038**

Students with higher study-time categories generally had higher average final grades in this dataset. This is an association and does not establish causation.

## 🤖 Machine Learning

A **Linear Regression** model was trained to predict the final grade.

### Test Set Performance

| Metric | Score |
|---|---:|
| MAE | 1.248 |
| RMSE | 1.815 |
| R² | 0.837 |

The model was evaluated on a held-out test set.

## 📈 Visualization

The project includes visualizations for:

- Final grade distribution
- Study time vs average final grade
- Absences vs final grade
- G2 vs final grade
- Actual vs predicted grades

## 🔗 Kaggle Notebook

[View the complete Kaggle Notebook](https://www.kaggle.com/code/vishalsharma5714/student-performance-analysis-prediction)

## 🚀 Future Improvements

- Compare multiple Machine Learning algorithms
- Perform cross-validation
- Tune model hyperparameters
- Analyze feature importance
- Experiment with different feature sets
- Build an interactive prediction application

## 👨‍💻 Author

**Vishal Sharma**

Computer Science & Engineering Student

GitHub: [@vishalexplore](https://github.com/vishalexplore)
