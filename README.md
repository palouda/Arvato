# Arvato
Project for Udacity to create Customer Segmentation for Arvato Bertelsmann and create a predictive model

## Table of Contents

- [Project Overview](#projectoverview)
- [Technical Overview](#technicaloverview)
- [Requirements](#requirements)



***

<a id='projectoverview'></a>

## 1. Project Overview

In this project, we are provided with demographic data of customers of a mail-order company in Germany and demographic data of general population of Germany. Using this data, we are required to identify new customers for the company.

We approach this project in 3 phases:
* Process the given data of a dataset of the general population and another dataset of Aravato customers
* Use customer segmentation to analyze and process the data further so that a predictive model can be built
* Use Supervised Learning to build a model that predicts whether or not a given person is likely to become a customer

Goal of this project is to predict individuals who are most likely to become customers for a mail-order sales company in Germany.

Please find detailed overview of the project in blog post: https://cpalouda.medium.com/udacity-arvato-bertelsmann-project-789d20bf8513

<a id='technicaloverview'></a>

## 2. Technical overview:

Step by step workflow from data exploration, processing to inference is approached in a structured fashion. Because of the large volume of source data, we build preprocessing pipeline  to get rid of unnecessary and outlier data and implement Dimensionality Reduction and Clustering to identify segments. Due to the nature of the data (details in notebook), AUC/ROC is used as the evaluation metric for this project. Prediction for test set is to be submitted to Kaggle competition for evaluation.

Following concepts implemented and covered in detail in the notebook: 
* Data Exploration & Cleansing
* Dimensionality Reduction
* Clustering
* Supervised Learning
* Final Model Evaluation
* Feature Importance
* Analysis of identified important features in clusters to find relevance

## 3. Requirements

* Pandas
* Sklearn
* XGBoost

