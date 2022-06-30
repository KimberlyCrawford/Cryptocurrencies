# Cryptocurrencies

## Overview
Crypotocurrencies Data Analysis Using Unsupervised Machine Learning Techniques  

### Purpose
To convince Accountability Accounting to invest in the cutting-edge financial system of cryptocurrencies. 

- An unsupervised learning model was used because we were looking for any groupings, trends, or other information that could help us pitch cryptocurrencies to Accountability Accounting. Unsupervised learning is used when we don't yet know the question we're asking of the data. Is there anything at all the data can tell us?

## Dataset

[Crypto Dataset](http://localhost:8888/edit/UTBootcamp/Cryptocurrencies/Resources/crypto_data.csv)

## Deliverables

Deliverable 1: Preprocessing the Data for PCA 
Using Pandas, the dataset was preprocessed in order to perform PCA in Deliverable 2.

Deliverable 2: Reducing Data Dimensions Using PCA 
Using the Principal Component Analysis (PCA) algorithm, the dimensions of the X DataFrame was reduced to three principal components and placed in a new DataFrame.

Deliverable 3: Clustering Cryptocurrencies Using K-means 
Using the K-means algorithm, an elbow curve was created using hvPlot to find the best value for K from the pcs_df DataFrame created in Deliverable 2. The K-means algorithm was run to predict the K clusters for the cryptocurrencies’ data.

Deliverable 4: Visualizing Cryptocurrencies Results
Using scatter plots with Plotly Express and hvplot, the distinct groups that correspond to the three principal components was visualized. A table was created with all the currently tradable cryptocurrencies using the hvplot.table() function.

![3D_scatter_plot.png](https://github.com/KimberlyCrawford/Cryptocurrencies/blob/main/Resources/3D_scatter_plot.png)

![Tradeable.png](https://github.com/KimberlyCrawford/Cryptocurrencies/blob/main/Resources/Tradeable.png)

![New_dataframe.png](https://github.com/KimberlyCrawford/Cryptocurrencies/blob/main/Resources/New_dataframe.png)

![scatter_plot.png](https://github.com/KimberlyCrawford/Cryptocurrencies/blob/main/Resources/scatter_plot.png)

#### Module 18, Data Analysis & Visualization Certificate Program, UT Austin McCombs School of Business, 2021.
