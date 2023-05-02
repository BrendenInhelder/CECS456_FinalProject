# CECS456_FinalProject
Final Project for CECS456 ML @ CSULB\
Group 8\
Project: Carbon-Monoxide Prediction for Air-Quality Dataset\
Team Members: \
1	Nathan Lai\
2	Sarthak Nagrani\
3	Brenden Inhelder\
4	Onyedikachi Benjamin Okenwa\
5	Williams Nguyen\
6	Sopheak Chim
7 Dylan Ramos

# Task: Regression
## Tasks: 
Predict CO concentration: One of the main pollutants measured in this dataset is Carbon Monoxide (CO). A regression model is to be trained to predict the CO concentration based on the other measured variables such as temperature, humidity, and other pollutants.
## Data Set Information:
The dataset contains 9358 instances of hourly averaged responses from an array of 5 metal oxide chemical sensors embedded in an Air Quality Chemical Multisensor Device. The device was located on the field in a significantly polluted area, at road level,within an Italian city. <br> <br>
Data were recorded from March 2004 to February 2005 (one year)representing the longest freely available recordings of on field deployed air quality chemical sensor devices responses. Ground Truth hourly averaged concentrations for CO, Non Metanic Hydrocarbons, Benzene, Total Nitrogen Oxides (NOx) and Nitrogen Dioxide (NO2) and were provided by a co-located reference certified analyzer.<br> <br>
Evidences of cross-sensitivities as well as both concept and sensor drifts are present eventually affecting sensors concentration estimation capabilities. <br><br>
Missing values are tagged with -200 value. 
## Instructions/Directions:
The Air Quality dataset contains hourly measurements of air quality from an Italian city.\
&nbsp;&nbsp;&nbsp;&nbsp;1. Perform exploratory data analysis and feature selection 	\
&nbsp;&nbsp;&nbsp;&nbsp;2. Visualization\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.1. Plot the variable distribution using box plot, histogram, and provide a summary of your understanding               
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.2. Provide an insight on the outcome of the correlation matrix.\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.3. Plot the relevant graphs    \
&nbsp;&nbsp;&nbsp;&nbsp;3. Perform feature extraction using Principal Component Analysis (PCA). \
&nbsp;&nbsp;&nbsp;&nbsp;4. For Model selection, perform K-Fold Cross Validation on the regression models used. \
&nbsp;&nbsp;&nbsp;&nbsp;5. Design a regression model (use at  least 5 regression models) and perform hyperparameter tuning and document the results.\
Dataset:  https://archive.ics.uci.edu/ml/datasets/Air+Quality\
