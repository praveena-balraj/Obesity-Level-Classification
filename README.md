# Obesity Level Classification – End-to-End Data Pipeline

## Project Overview

This project focuses on building a structured data preprocessing and classification pipeline to estimate obesity levels based on eating habits, physical attributes, and lifestyle factors.

Using the UCI Obesity Dataset (2,111 records, 17 features), the objective was to design a reproducible workflow that handles data cleaning, feature engineering, model training, and evaluation.# Obesity-Level-Classification
End-to-end data preprocessing and machine learning pipeline for obesity level prediction using UCI dataset.

## Objectives

Clean and preprocess structured health-related data

Encode categorical variables

Scale numerical features

Train and compare classification models

Identify key predictors of obesity

## Dataset Information

Source: UCI Machine Learning Repository

Records: 2,111

Features: 17

Target Variable: NObeyesdad

## Target classes include:

Normal Weight

Overweight Level I

Overweight Level II

Obesity Type I

Obesity Type II

Obesity Type III

## Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

## Project Workflow

### 1️.Data Preprocessing

Missing value handling

Label Encoding (target variable)

One-Hot Encoding (categorical features)

Train-Test Split (80/20)

Feature Scaling using StandardScaler

### 2.Exploratory Data Analysis (EDA)

Class distribution visualization

Histograms for feature distribution

Correlation heatmap

Feature-to-target relationship analysis

### 3️.Model Training

**Logistic Regression**

Multinomial classification

Accuracy: ~85%

**Random Forest**

100 decision trees

Accuracy: ~92%

Better handling of non-linear relationships

## Model Comparison

**Model	             Accuracy**
Logistic Regression	   ~85%
Random Forest	         ~92%

**Random Forest outperformed Logistic Regression.**

## Skills Demonstrated

- Structured data preprocessing

- Handling mixed-type datasets

- Feature engineering

- Model evaluation

- Avoiding data leakage

- Reproducible ML workflow

## Author

Praveena Kollasseril Balraj
MSc Advanced Computing (Big Data)
University of the West of Scotland



