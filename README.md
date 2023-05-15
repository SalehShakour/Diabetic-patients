# Diabetic Patients

This repository contains a project focused on analyzing and predicting the risk of diabetes in patients. The goal of this project is to develop a predictive model that can assist in identifying individuals who are at a higher risk of developing diabetes based on certain features.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)


## Introduction

Diabetes is a chronic condition that affects millions of people worldwide. Early detection and management of diabetes can significantly improve patient outcomes. This project aims to leverage machine learning techniques to analyze various factors and predict the risk of diabetes in patients. By identifying individuals who are at higher risk, healthcare providers can focus their efforts on preventive measures and interventions.

## Features

The project includes the following features:

1. Data preprocessing: Cleansing and preparing the dataset for analysis.
2. Exploratory data analysis (EDA): Analyzing the dataset to gain insights into the data distribution, correlations, and potential patterns.
3. Feature engineering: Selecting and transforming relevant features for training the model.
4. Model development: Implementing machine learning algorithms, including k-means clustering and k-nearest neighbors (KNN), to build predictive models.
5. Model evaluation: Assessing the performance of the trained models using appropriate metrics.
6. Prediction: Utilizing the trained models to predict the risk of diabetes in new patients.

## Installation

To use this project, please follow these steps:

1. Clone the repository:
```
git clone https://github.com/SalehShakour/Diabetic-patients.git
```
2. Install the required dependencies:
```
pip install -r requirements.txt
```

## Dataset

The dataset used in this project is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/00296/). It represents 10 years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks, containing over 50 features representing patient and hospital outcomes. The dataset was extracted from encounters that satisfied specific criteria:

- It is an inpatient encounter (a hospital admission).
- It is a diabetic encounter, where any kind of diabetes was entered into the system as a diagnosis.
- The length of stay was at least 1 day and at most 14 days.
- Laboratory tests were performed during the encounter.
- Medications were administered during the encounter.

The dataset includes attributes such as patient number, race, gender, age, admission type, time in the hospital, medical specialty of the admitting physician, number of lab tests performed, HbA1c test result, diagnosis, number of medications, diabetic medications, number of outpatient, inpatient, and emergency visits in the year before hospitalization, and more.

Detailed descriptions of all the attributes can be found in [Table 1](https://archive.ics.uci.edu/ml/machine-learning-databases/00296/Dataset%20description.docx) provided in the dataset.

The dataset was originally described in the paper titled "Impact of HbA1c Measurement on Hospital Readmission Rates: Analysis of 70,000 Clinical Database Patient Records" by Beata Strack, Jonathan P. DeShazo, Chris Gennings, Juan L. Olmo, Sebastian Ventura, Krzysztof J. Cios, and John N. Clore.

If you use this dataset, please cite the following paper:

Beata Strack, Jonathan P. DeShazo, Chris Gennings, Juan L. Olmo, Sebastian Ventura, Krzysztof J. Cios, and John N. Clore, “Impact of HbA1c Measurement on Hospital Readmission Rates: Analysis of 70,000 Clinical Database Patient Records,” BioMed Research International, vol. 2014, Article ID 781670, 11 pages, 2014.

You can access the dataset at the following link: [Diabetes 130-US hospitals for years 1999-2008](https://archive.ics.uci.edu/ml/machine-learning-databases/00296/)

Please make sure to cite the original paper if you use this dataset in your research or project.

## Model

The project implements two machine learning algorithms:

1. **K-means clustering**: This algorithm is used for unsupervised learning and can help identify patterns and clusters within the dataset.
2. **K-nearest neighbors (KNN)**: This algorithm is used for classification and can predict the risk of diabetes based on the characteristics of similar patients.

The implementation details of these algorithms can be found within the code of the project.

## Results

The results of the project can be visualized to gain insights and evaluate the performance of the models.

### K-means Clustering Results Visualization with PCA

The k-means clustering results can be visualized using Principal Component Analysis (PCA) to reduce the dimensionality of the data. By plotting the data points in a scatter plot, colored according to their assigned cluster labels, the grouping and distribution of patients based on similar characteristics can be observed.

### K-nearest Neighbors (KNN) Results Visualization with Plots

The results of the K-nearest Neighbors (KNN) algorithm can be visualized using various plots. For classification tasks, a confusion matrix can be used to evaluate the model's performance in classifying patients into different risk groups. Other plots, such as precision-recall curves or receiver operating characteristic (ROC) curves, can provide insights into the model's effectiveness and trade-off between true positive rate and false positive rate.

By visualizing the results of k-means clustering and KNN, we can interpret the findings, assess the model performance, and communicate the insights effectively.

Feel free to customize and expand upon this section based on the specific visualizations and plots generated in your project.

Remember to include any specific instructions on how to access and interpret the visualizations in your project's documentation.
