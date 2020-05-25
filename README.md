# Analysing the Causes of Heart Disease

## Problem Statement
In United States, heart disease is responsible for 1 in 4 deaths each year, i.e. in 2019 about 647,000 Americans died from heart disease!

It is the leading cause of death for people of most racial and ethnic groups in the United States, including African American, American Indian, Alaska Native, Hispanic, and white men. 

High blood pressure, high blood cholesterol, and smoking are key factors for heart disease and
about half of Americans (47%) have at least one of these three risk factors!

## About the dataset

Source : https://archive.ics.uci.edu/ml/datasets/Heart+Disease
The dataset originally contains 76 variables, but all published experiments refer to using 14 of them. 
The data is complete with and has no missing values 
The data has 303 observations with 6 continuous variables and 8 discrete variables

## Overview

1. The idea behind the analysis is that the diagnosis of heart disease is a result of combination of various clinical factors provided in the data. 
2. From various sources it is known that factors such as gender, chest pain, age, cholesterol contribute to heart disease, therefore the analysis has been structured keeping that as baseline.
3. To deep dive into data we have implemented Unsupervised learning methods along with EDA & Supervised learning methods to gauge the predictive power

## Conclusion

1. Working on Unsupervised learning algorithms tells us that k-means & hierarchical techniques were able to cluster the data in 2 clusters based on Euclidean and Gower distance between data points. The divided clusters had .28 & .24 misclassification rate which is moderate.
2. Further, we worked on understanding the feature importance using PCA technique that brought to our notice that close to 20 predictors out of 29 hot encoded are required to explain 98% of variance in data. 
3. 70% of predictors are called out as important, hence we decide to include all in our further analysis of Supervised classification models.
