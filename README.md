# Student Marks Prediction Model

This project aims to predict student marks based on various factors including Hours Studied, Previous Scores, Extracurricular Activities, Sleep Hours, and Sample Question Papers Practiced. The model is built using a multiple regression approach from scratch, without relying on any Python machine learning libraries.

## Project Overview

The goal of this project is to develop a predictive model that can accurately estimate student marks based on the following features:

- Hours Studied
- Previous Scores
- Extracurricular Activities
- Sleep Hours
- Sample Question Papers Practiced

## Dataset

The dataset used in this project consists of student information with the following columns:

- `Hours Studied`: Number of hours the student studied.
- `Previous Scores`: Previous academic scores of the student.
- `Extracurricular Activities`: Involvement in extracurricular activities (measured on a scale or binary).
- `Sleep Hours`: Number of hours the student sleeps per night.
- `Sample Question Papers Practiced`: Number of sample question papers practiced by the student.
- `Performance Index`: The marks scored by the student (target variable).

## Model

The model is built using multiple linear regression implemented from scratch. The following steps were performed:

1. **Data Preprocessing**:

   - Handling missing values.
   - Scaling or Normalizing features if necessary.

2. **Model Training**:

   - Split the data into training and test sets.
   - Train a multiple regression model on the training data using custom functions for gradient descent and cost calculation.

3. **Evaluation**:
   - Evaluate the model using Mean Squared Error (MSE) and R-squared (R²) metrics.

## Results

The final model achieved the following impressive results on the test set:

- **Mean Squared Error (MSE): 4.24**
- **R-squared (R²): 0.98**
- **Accuracy within a tolerance of 4.5: 96.60%**

These metrics indicate that the model is highly accurate, explaining 98% of the variance in student marks with a relatively small average error.
