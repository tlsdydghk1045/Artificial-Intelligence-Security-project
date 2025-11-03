# Project Title: Static Analysis-based Android Botnet Detection

## 1. Project Overview
This project aims to develop a machine learning model for detecting Android botnets using static analysis of application features. The goal is to classify Android applications as 'Benign' or 'Botnet' prior to execution, enhancing mobile security.

## 2. Dataset Used
* **Name:** Android Botnet Detection Dataset
* **Source:** https://www.kaggle.com/datasets/saeedseraj/botdroid-android-botnet-detection/data
* **Description:** Contains approximately ~7,000 Android app samples (Benign/Botnet) with ~340 static features (permissions, API calls, intents, commands).

## 3. Planned Models & Approach
* **Machine Learning Models:** Initial plan includes using classical ML models like Random Forest, Logistic Regression, or Gradient Boosting Classifiers due to the tabular nature of the static features.
* **Approach:**
    * Data Preprocessing: Handling missing values, encoding categorical features.
    * Feature Engineering: Analyzing feature importance to select optimal features.
    * Model Training: Splitting data into training/testing sets, training selected models.
    * Evaluation: Assessing model performance using metrics like accuracy, precision, recall, and F1-score.

## 4. Training Recipes & Expected Results
* **Planned Workflow:**
    1.  Load and preprocess `Botnet_dataset.csv`.
    2.  Perform Exploratory Data Analysis (EDA) on features and target distribution.
    3.  Split data into training and test sets (e.g., 80% train, 20% test).
    4.  Train selected ML model (e.g., Random Forest Classifier) on the training data.
    5.  Evaluate the model on the test data and report performance metrics.
* **Expected Output:** A trained model capable of classifying new Android apps with high accuracy.

## 5. Project Deliverables
* Presentation Slides (PPT/PDF)
* This GitHub Repository (containing `README.md` and planned code)
