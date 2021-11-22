# Cryptocurrencies

## Overview
Crypotocurrencies Data Analysis Using Unsupervised Machine Learning Techniques  

### Purpose
To convince Accountability Accounting to invest in the cutting-edge financial system of cryptocurrencies. 

- An unsupervised learning model was used because we were looking for any groupings, trends, or other information that could help us pitch cryptocurrencies to Accountability Accounting. Unsupervised learning is used when we don't yet know the question we're asking of the data. Is there anything at all the data can tell us?

Built several machine learning models to predict

### Dataset

The [iris dataset](https://archive.ics.uci.edu/ml/datasets/iris) from the University of California, Irvine (UCI) Machine Learning Repository.

### Technologies Used

You'll work primarily with the  We'll 

- Created and Implemented a machine learning model in Python primarily using the K-means algorithm, the main unsupervised algorithm that groups similar data into clusters.
- Speeded up the process using principal component analysis (PCA), which employs many different features.. 
- Trained the model ?? 
- Used Scikit-learn, a Python machine learning library, to implement a linear regression model. Used Plotly and hvPlot
- Used 
- Created predictions.

The basic pattern for supervised learning used in this linear regression example:

- Split the data into input (X) and output (y).
- Create an instance of the model with model = LinearRegression().
- Train the model with the dataset with model.fit(X,y).
- Create predictions with y_pred = model.predict(X).

### Resources

## Results

Deliverable 1: Preprocessing the Data for PCA (30 points)
Deliverable 1 Instructions
Using your knowledge of Pandas, you’ll preprocess the dataset in order to perform PCA in Deliverable 2.



Deliverable 2: Reducing Data Dimensions Using PCA (20 points)
Deliverable 2 Instructions
Using your knowledge of how to apply the Principal Component Analysis (PCA) algorithm, you’ll reduce the dimensions of the X DataFrame to three principal components and place these dimensions in a new DataFrame.

Deliverable 3: Clustering Cryptocurrencies Using K-means (30 points)
Deliverable 3 Instructions
Using your knowledge of the K-means algorithm, you’ll create an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame created in Deliverable 2. Then, you’ll run the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.

Deliverable 4: Visualizing Cryptocurrencies Results (30 points)
Deliverable 4 Instructions
Using your knowledge of creating scatter plots with Plotly Express and hvplot, you’ll visualize the distinct groups that correspond to the three principal components you created in Deliverable 2, then you’ll create a table with all the currently tradable cryptocurrencies using the hvplot.table() function.

## Summary

In supervised learning, first a model is initiated, or a template for the algorithm is created. Then it will analyze the data and attempt to learn patterns, which is also called fitting and training. After the data has been fit and trained, it will then make predictions.