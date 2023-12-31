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
4. BMI
5. Diabetes Pedigree Function
6. Age

## Features

- Diabetes prediction model
- Data preprocessing and visualization
- Sample datasets for training and testing

## Getting Started

git clone https://github.com/StevenWong0121/Diabetes-Model.git

OR

Download the pkl files from *models* Directory and loaded into Jupyter Notebook for data prediction

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
    macro avg      Avg                      Avg             Avg                   Total instances
    weighted avg   Weight Avg               Weight Avg      Weighted Avg          Total Instances

Negative Precision = True Negatives / Total Actual Negatives<br>
Positive Presision = True Positives / Total Actual Positives<br>


Specificty = True Negatives / Total predicted Negatives<br>
Sensitivity = True Positives / Total predicted Positives<br>


Negative F1 Score = (2 * Negative Precision * Specificity) / (Negative Precision + Specificity)<br>
Positive F1 Score = (2 * Positive Precision * Sensitivity) / (Positive Precision + Sensitivity)<br>

Accuracy = (True Positives + True Negatives) / Total Instances


## Acknowledgement

This dataset is provided on Kaggle.com by Akshay Dattatray Khare, click on the link below for more information:
https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset
