# Machine Learning-Based Prediction of Pasteurized Milk Quality and Shelf-Life Status

## Project Overview

This project focuses on predicting the **shelf-life status of pasteurized milk** using machine learning. The study considers important milk quality parameters along with refrigerated storage conditions to classify samples as **Acceptable or Spoiled**.

> **Note:** The dataset used in this project is a synthetically generated dataset created for academic and machine learning practice purposes.

## Objectives

- Analyze pasteurized milk quality during refrigerated storage.
- Study the relationship between **storage conditions and milk quality parameters**.
- Identify patterns associated with milk spoilage.
- Develop machine learning models to classify milk samples as **Acceptable or Spoiled**.
- Compare the performance of different classification algorithms.

## Dataset

The dataset contains **1,500 observations** with the following variables:

| Feature | Description |
|---|---|
| Storage_Temperature_C | Storage temperature in °C |
| Storage_Time_Days | Storage duration in days |
| pH | Milk pH |
| Titratable_Acidity_pct | Titratable acidity (%) |
| Microbial_Load_log_CFU_mL | Microbial load |
| Sensory_Score | Sensory quality score |
| Shelf_Life_Status | Target variable: Acceptable or Spoiled |

## Exploratory Data Analysis

The analysis includes:

- Dataset structure and descriptive statistics
- Missing-value and duplicate checking
- Shelf-life status distribution
- Correlation analysis
- Feature relationships and visualization

## Machine Learning Models

Three classification algorithms were implemented:

1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**

The models were trained using a **train-test split** and evaluated using classification accuracy and confusion matrices.

## Model Performance

| Model | Accuracy |
|---|---:|
| Logistic Regression | 95.33% |
| Decision Tree | 99.67% |
| Random Forest | 99.67% |

## Feature Importance

The Random Forest model identified the following features as important for classification:

- Titratable Acidity
- pH
- Microbial Load
- Storage Time
- Sensory Score
- Storage Temperature

## Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

## Project Workflow

```text
Data Generation
      ↓
Data Loading & Inspection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Feature Selection
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Feature Importance Analysis
