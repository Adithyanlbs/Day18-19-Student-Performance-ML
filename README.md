# Day 18 & 19 — ML Student Performance Prediction

## Project Overview

This project follows a complete machine learning workflow to analyze and predict student exam performance.

## Workflow

- Exploratory Data Analysis
- Data quality assessment
- Missing-value analysis
- Numerical and categorical variable identification
- Correlation analysis
- Outlier analysis
- Data preprocessing
- Train/test split
- Multiple Linear Regression
- Regression prediction and evaluation
- Pass/Fail classification
- Logistic Regression
- Confusion matrix
- Accuracy
- Precision
- Recall
- F1-score
- Training vs testing comparison
- Overfitting and underfitting analysis
- Business/statistical insights

## Regression Target

`exam_score`

## Classification Target

Students are classified as:

- Pass: `exam_score >= 50`
- Fail: `exam_score < 50`

## Key Findings

- `study_hours_per_day` has the strongest observed relationship with exam score, with a correlation of approximately 0.83.
- `mental_health_rating` has a positive relationship with exam performance.
- `social_media_hours` and `netflix_hours` show negative relationships with exam score.
- Linear Regression achieves approximately 0.90 R² on the test data.
- Logistic Regression achieves approximately 96% test accuracy for Pass/Fail classification.
- Training and testing performance are close, indicating no strong evidence of overfitting or underfitting.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Files

`Day18_19_ML_Student_Performance_Prediction.ipynb`

Contains the complete EDA, preprocessing, regression model, classification model, evaluation, insights, and conclusion.

## Conclusion

The analysis indicates that study habits and other student lifestyle factors contain useful information for predicting academic performance. The models show strong predictive performance on the test data and reasonable generalization from training to unseen data.
