The Spark Foundation Internship Projects
This repository contains the projects completed during my internship at The Spark Foundation. The projects demonstrate various data science and machine learning techniques applied to real-world datasets.

Table of Contents
Introduction
Project 1: Linear Regression on Student Scores
Overview
Dataset
Implementation
Results
Conclusion
Project 2: K-Means Clustering on Iris Dataset
Overview
Dataset
Implementation
Results
Conclusion
How to Run the Code
Requirements
Contact
Introduction
This repository contains two key projects I completed as part of The Spark Foundation (TSF) internship. The projects demonstrate my ability to apply machine learning algorithms to solve specific problems and extract meaningful insights from data.

Project 1: Linear Regression on Student Scores
Overview
The objective of this project was to predict student scores based on the number of hours they studied. A simple linear regression model was used to create predictions and evaluate the model's performance.

Dataset
Source: Provided by The Spark Foundation.
Format: CSV
Columns: Hours (Independent Variable), Scores (Dependent Variable)
Implementation
Data Loading: Loaded the dataset using pandas.
Data Visualization: Plotted the data to observe the relationship between study hours and scores.
Model Training: Applied a linear regression model using scikit-learn.
Prediction: Predicted scores based on new study hours data.
Evaluation: Evaluated the model using Mean Absolute Error (MAE) and R-squared metrics.
Results
MAE: 2.97
R-squared: 0.9678
predicted score for 9.5 hours of study : 94.80
The model performed well, showing a strong correlation between study hours and scores.
Conclusion
The linear regression model effectively predicted student scores based on study hours. The high R-squared value indicates that the model fits the data well.

Project 2: K-Means Clustering on Iris Dataset
Overview
This project involved clustering the famous Iris dataset using the K-Means algorithm to classify the iris flowers into three distinct species.

Dataset
Source: provided by The Spark Foundation
Format: CSV
Columns: Id, SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm, Species
Implementation
Data Loading: Loaded the Iris dataset using pandas.
Data Preprocessing: Performed label encoding on the Species column.
Model Training: Applied the K-Means clustering algorithm to find the optimum number of clusters.
Evaluation: Evaluated the clusters by comparing them to the actual species labels using a confusion matrix.
Results
Confusion Matrix: The confusion matrix indicated some misclassification, but the clusters were mostly accurate.
Cluster Centers: The cluster centers were calculated, representing the mean of the features for each cluster.
Conclusion
The K-Means algorithm was able to correctly classify a majority of the data points. Further tuning or additional features might improve the classification accuracy.


