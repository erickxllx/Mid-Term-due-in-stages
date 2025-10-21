Dataset Proposal – Student Academic Performance Prediction

Author: Ing. Erick Banegas
Date: October 2025
Dataset Source: Kaggle – Student Academic Performance Dataset

1. Overview

This dataset contains detailed academic and demographic information from 1,000 students, including their math, reading, and writing scores, attendance rate, study hours, parental education, internet access, lunch type, and extracurricular activities. The dataset also includes a final_result column that indicates whether each student passed or failed.

2. Objective

The goal of this project is to predict student academic performance — specifically whether a student will pass or fail — based on academic and socio-educational factors.

3. Before and After Data Processing

Before processing:
The raw dataset includes string labels, missing values, and inconsistent categorical data (e.g., “Yes/No” or “Standard/Free or reduced”). Numerical fields such as attendance rate and study hours vary widely and may require normalization.

After processing:
Data will be cleaned, missing values handled, and categorical features encoded into numerical values. Irrelevant columns like name or student_id will be removed. The processed dataset will contain only relevant, standardized variables ready for model training and evaluation.

4. Proposed Tasks

Data Exploration: Examine dataset structure, detect outliers, and study feature correlations.

Data Preprocessing: Handle missing values, normalize numerical data, and encode categorical variables.

Model Development: Train classification models (e.g., Logistic Regression, Random Forest) to predict final_result.

Evaluation: Assess model performance using accuracy, precision, recall, and F1-score.

Visualization: Create visual comparisons between raw and processed data, and show prediction outcomes.

5. Expected Outcome

The final model will help identify students at risk of failure early in the semester. Insights gained will assist educators in developing targeted strategies to improve academic success and student engagement.