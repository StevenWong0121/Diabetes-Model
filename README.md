# Diabetes-Model
Welcome to the Diabetes Tracking Model repository. This project provides a machine learning model to predict and track diabetes-related information.


## Table of Contents

- [About](#about)
- [Features](#features)
- [Getting Started](#getting-started)
- [Report Undertsanding](#report-understanding)
- [Acknowledgement](#acknowledgement)


## About

This repository contains a Jupyter notebook where been developed a machine learning model for diabetes tracking. 
The model uses various features  as below to predict and track diabetes-related information:
1. Pregnancies
2. Gluclose level
3. Blood Pressure
4. Skin Thckness
5. Insulin level
6. BMI
7. Diabetes Pedigree Function
8. Age

## Features

- Diabetes prediction model
- Data preprocessing and visualization
- Sample datasets for training and testing

## Getting Started

git clone https://github.com/StevenWong0121/Diabetes-Model.git

## Report Understading

Confusion Matrix:

                        Actual Pasitive            Actual Negative
Predicted Positive      True Positive              False Positive
Predicted Negative      False Negative             True Negative

Classification Report:

                  precision                 recall          f1-score              support
           0      Negative Precision        Specificty      Negative Score        Total Actual Negatives
           1      Positive Presicion        Sensitivity     Positive Score        Total Actual Positives

    accuracy                                                Accuracy              Total Instances
   macro avg       Avg                      Avg             Avg                   Total instances
weighted avg       Weight Avg               Weight Avg      Weighted Avg          Total Instances

Negative Precision = True Negatives / Total Actual Negatives
Positive Presision = True Positives / Total Actual Positives 

Specificty = True Negatives / Total predicted Negatives
Sensitivity = True Positives / Total predicted Positives

Negative F1 Score = (2 * Negative Precision * Specificity) / (Negative Precision + Specificity)
Positive F1 Score = (2 * Positive Precision * Sensitivity) / (Positive Precision + Sensitivity)

Accuracy = (True Positives + True Negatives) / Total Instances


## Acknowledgement

This dataset is provided on Kaggle.com by Akshay Dattatray Khare, click on the link below for more information:
https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset
