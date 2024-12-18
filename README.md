# Premium Predictions: Cracking the Insurance Puzzle

# A Kaggle Competition Notebook on Regression with an Insurance Dataset

## 📖 Overview

Welcome to the 2024 Kaggle Playground Series! This competition offers an engaging dataset to sharpen your machine learning skills. Each month, participants tackle new challenges with approachable datasets.

Objective: Predict insurance premiums based on various factors.

## 🚀 Timeline

Start Date: December 1, 2024
Final Submission Deadline: December 31, 2024 (11:59 PM UTC)

## ⚠️ Note: Team mergers and entry deadlines are the same as the final submission deadline.

## 🏆 Evaluation

Submissions are evaluated using the Root Mean Squared Logarithmic Error (RMSLE) metric.

## 📄 Submission File Format

Your submission file must contain predictions for each id in the test dataset. The required format is:

id,Premium Amount
1200000,1102.545
1200001,1102.545
1200002,1102.545
...

## 🔍 About the Playground Series
The Tabular Playground Series focuses on lightweight challenges for learning and skill-building in machine learning. These challenges:

Use synthetic datasets inspired by real-world data.
Allow quick iterations with model and feature engineering ideas.
Encourage exploration of visualizations and model performance.
Why synthetic data? Synthetic datasets enable competitions with interesting features while protecting test labels.

## 🏅 Prizes

1st Place: Choice of Kaggle merchandise
2nd Place: Choice of Kaggle merchandise
3rd Place: Choice of Kaggle merchandise
Note: To encourage broader participation, winners can only receive merchandise once during this series.

## 📊 Dataset Description

The dataset is synthetically generated from the Insurance Premium Prediction dataset and includes:

train.csv: Training dataset with the target variable Premium Amount.
test.csv: Test dataset to predict Premium Amount.
sample_submission.csv: Sample file demonstrating submission format.

Download Links:
train.csv
test.csv
sample_submission.csv

Dataset Details:

Size: 332.74 MB
Format: CSV
License: Apache 2.0

## 📁 Files

File Name	Description	Size	Download Link

train.csv	Training data with 43 features and target value	332.74 MB	Download here https://1drv.ms/f/s!AmlaN4R9CsYBhrZiNf7JhVxe7yXojQ?e=Pe602e

test.csv	Test data for predictions	332.74 MB	Download here https://1drv.ms/f/s!AmlaN4R9CsYBhrZiNf7JhVxe7yXojQ?e=Pe602e

sample_submission.csv	Example submission file	13.6 MB	Download here https://1drv.ms/f/s!AmlaN4R9CsYBhrZiNf7JhVxe7yXojQ?e=Pe602e

## ⚙️ Getting Started
Download the data using the Kaggle CLI:

kaggle competitions download -c playground-series-s4e12

## Table of Contents

0. **Introduction**
   - [Overview of Supervised Learning](#overview-of-supervised-learning)
   - [Objective: Regression Task](#objective-regression-task)
   - [Why It's Multiple Linear Regression](#why-its-multiple-linear-regression)
1. **Import Required Libraries**
2. **Load and Inspect the Data**
3. **Preprocessing**
4. **Train-Test Split for Cross-Validation**
5. **Cross-Validation with XGBoost**
6. **Model Training on Full Data and Cross-Validation**
7. **Predict on Test Data and Prepare Submission**
8. **Cross-Validation with K-Fold**
9. **Recommendations for Improvement**
   - [Hyperparameter Tuning](#hyperparameter-tuning)
   - [Feature Engineering](#feature-engineering)
   - [Model Ensembling](#model-ensembling)
   - [Statistical Aspects of Multiple Linear Regression](#statistical-aspects-of-multiple-linear-regression)
   - [Test Polynomial Regression](#test-polynomial-regression)
10. **Submit the File to Kaggle**


## 📜 Citation
Walter Reade and Elizabeth Park.
Regression with an Insurance Dataset.
Kaggle Playground Series S4E12, 2024.

## 🔗 Additional Information
For more details about this challenge, visit the Kaggle competition page.
