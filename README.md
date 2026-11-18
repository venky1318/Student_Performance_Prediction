# Task 40 – Student Performance Prediction Using Machine Learning

## Project Overview

This project focuses on predicting student academic performance using Machine Learning techniques.

The Students Performance in Exams dataset is used to analyze student information and predict average examination scores.

The project includes data exploration, data cleaning, feature engineering, exploratory data analysis, feature selection, model training, prediction, and evaluation.

## Objectives

- Understand and explore student performance data.
- Identify and handle missing values and duplicate records.
- Perform exploratory data analysis.
- Create an average score feature.
- Separate input features and target variable.
- Train a Machine Learning model.
- Predict student performance.
- Evaluate model performance.

## Dataset Description

The project uses the Students Performance in Exams dataset.

Dataset size: 1,000 student records.

Features include:
- Gender
- Race/Ethnicity
- Parental Education
- Lunch
- Test Preparation
- Math Score
- Reading Score
- Writing Score

The target variable is Average Score, calculated using the three subject scores.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab
- Jupyter Notebook

## Machine Learning Algorithm

**Random Forest Regressor**

The model uses categorical student information to predict average examination scores.

Training/testing split: 80:20.

## Project Workflow

1. Import required libraries.
2. Load the student performance dataset.
3. Explore dataset information.
4. Clean the dataset.
5. Handle missing and duplicate values.
6. Perform feature engineering.
7. Conduct exploratory data analysis.
8. Select input features and target variable.
9. Split data into training and testing sets.
10. Encode categorical variables.
11. Train Random Forest Regressor.
12. Generate predictions.
13. Evaluate model performance.
14. Visualize actual vs predicted values.
15. Export datasets and model.

## Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

Actual evaluation values are available in `evaluation_summary.csv`.

## Visualizations

The project includes:
- Average score distribution.
- Gender-wise performance.
- Test preparation analysis.
- Subject score comparison.
- Correlation heatmap.
- Actual vs predicted scores.
- Prediction error distribution.
- Feature importance.

## Project Files

- `Task_40_Student_Performance_Prediction.ipynb` – Complete notebook.
- `StudentsPerformance.csv` – Original dataset.
- `cleaned_student_performance.csv` – Cleaned dataset.
- `student_features.csv` – Selected input features.
- `student_target.csv` – Target variable.
- `student_predictions.csv` – Actual and predicted scores.
- `evaluation_summary.csv` – Model evaluation results.
- `feature_importance.csv` – Feature importance values.
- `student_performance_model.joblib` – Trained model.
- `requirements.txt` – Required libraries.
- `project_report.pdf` – Project documentation.
- `charts/` – Generated visualizations.
- `screenshots/` – Execution screenshots.

## How to Run

1. Clone or download this repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Open the Jupyter Notebook.
4. Upload the original CSV dataset if required.
5. Execute all notebook cells sequentially.
6. Review predictions and evaluation results.

## Conclusion

This project demonstrates the use of Machine Learning for student performance prediction.

Data cleaning, visualization, feature engineering, and Random Forest Regression are used to build a complete beginner-level prediction project.

The project provides practical experience in the Machine Learning workflow.

**Note:** This is an educational project. Predictions should not be used to make high-stakes decisions about students.
