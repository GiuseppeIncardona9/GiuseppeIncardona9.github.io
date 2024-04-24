---
title: "Machine Learning Model For Predicting Coronary Heart Disease"
excerpt: "The project involves developing a machine learning model to predict Coronary Heart Disease (CHD) among males in a high-risk area of the Western Cape, South Africa. 
The research team applies various supervised machine learning algorithms to determine the most effective model based on performance metrics such as accuracy, precision, and 
recall. Key health indicators like systolic blood pressure, tobacco usage, and LDL cholesterol levels are analyzed for their association with CHD. After a rigorous testing 
process that includes ten-fold stratified cross-validation, the Gaussian Naïve Bayes model is identified as particularly suitable due to its high sensitivity, which is crucial 
for diagnosing CHD and ensuring fewer cases go undiagnosed. This choice underscores the importance of patient safety, aiming to maximize the detection of all potential CHD cases. 
<br/><img src='/images/ML.webp'>"
collection: portfolio
---

The project focuses on predicting Coronary Heart Disease (CHD) among males in a high-risk area of Western Cape, South Africa using supervised machine learning algorithms. 
The objective is to identify the most effective algorithm for this purpose by applying a variety of classifiers to health and lifestyle data and evaluating their performance 
through multiple metrics.
The project starts with an exploratory data analysis, where the dataset is thoroughly analysed to understand the characteristics and distribution of factors like systolic blood 
pressure, tobacco usage, LDL cholesterol levels, adiposity and age in individuals with and without CHD. This phase also explores the impact of family history on CHD prevalence.
Following the analysis, several machine learning models including Logistic Ridge Regression (LRR), Support Vector Machine (SVM), K-Nearest Neighbor (K-NN), 
Linear Discriminant Analysis (LDA), Quadratic Discriminant Analysis (QDA), and Gaussian Naïve Bayes (GaussianNB) are evaluated. The evaluation uses a ten-fold stratified 
cross-validation approach to handle the dataset's class imbalance, and performance is assessed using accuracy, F1 score, precision, recall, and ROC AUC metrics.
The final phase involves selecting the optimal model. The study confirms the "No Free Lunch" theorem, indicating no single model is best for all scenarios. 
However, specific models excel in important medical metrics. While Logistic Ridge Regression shows high accuracy and precision, Naïve Bayes is chosen for its high recall, 
making it highly effective in reducing undiagnosed CHD cases. This choice underscores the project's emphasis on maximizing patient safety by prioritising the detection of 
potential CHD cases, even at the risk of some false positives. The code and report for this project can be found [here](https://github.com/GiuseppeIncardona9/Data-Driven-Projects/tree/main/Machine%20Learning%20Model%20%20For%20Predicting%20Coronary%20Heart%20Disease)
