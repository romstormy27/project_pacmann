# Pacmann Project Lab Data Science Final Project: IVF Prediction Task

## Description
description goes here

## 1. Data Preparations

![data preparations flowchart](../Figures/pacmann_ml_project_diagrams.png)

The first step was to look forward for each features in the dataset due to large numbers of them.
So, the first step to reduce them was to drop all the features that had NaN values more than 10%.

From initial 95 features, we only kept 57 features + 1 target features.

After that, the reduced dataset then splitted into train, validation, and test dataset with proportion of 60:20:20.

The splitting was done using ==sklearn.preprocess.train_test_split==