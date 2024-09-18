# Basic Mental Health Predictor

This project is a **Basic Mental Health Predictor**, which takes several input factors and predicts whether a person may have a potential mental health issue using a machine learning algorithm (Decision Tree Classifier).

## Input Factors

The predictor takes the following inputs:

- **Age**
- **Stress Level**
- **Sleep Hours**
- **Exercise Hours**
- **Work Hours**
- **Social Support**
- **Diet Quality**
- **Financial Stress**
- **Alcohol Consumption**
- **Smoking Habit**

## Machine Learning Model

A **Decision Tree Classifier** is used to predict whether the user is at risk for mental health issues based on the input factors.

## Tools & Libraries Used

- **Numpy**: For numerical operations
- **Pandas**: For data manipulation and analysis
- **Scikit-learn (sklearn)**:
  - **train_test_split**: To split the dataset for training and testing
  - **Decision Tree Classifier**: The machine learning algorithm used for prediction
- **Streamlit**: For building a web app interface to interact with the predictor

## Methodology

1. The predictor collects basic information about the user, including age, stress level, sleep patterns, exercise habits, and more.
2. The inputs are then processed and fed into a **Decision Tree Classifier** model.
3. The model predicts whether the user is likely to face mental health issues based on the provided factors.

## Web Application

The web application was built using **Streamlit** to provide an easy-to-use interface where users can input their details and receive predictions about their mental health.


