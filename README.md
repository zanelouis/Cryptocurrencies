# Cryptocurrencies

## Overview
In this module, unsupervised learning is used to process, cluster, reduce the dimensions and reduce the principal components using PCA on cryptocurrency data. Data visualizations are used to group the cryptocurrencies by utilizing clustering algorithms.

## Resources
- Data Source: LoanStats_2019Q1.csv
- Software: Python 3.7.9, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3, NumPy (v1.11 or later), hvplot.pandas, Scikit-learn (v0.21 or later)

## Process
1. Remove cryptocurrencies that are not being traded and that do not have a defined algorithm
2. Drop IsTrading column
3. Drop rows that have at least one null value and if coins have not been mined
4. Create variables using get_dummies for the text features
5. Scale and standardize the DataFrame
6. Apply the Principal Component Analysis (PCA) algorithm, by reducing the dimensions to 3 principal components
7. Create an instance of the K-means algorithm and make predictions
8. Create an elbow curve using hvPlot
9. Plot clusters using a 3D scatter plot and showing each data point as the CoinName and Algorithm on hover by Class


![image](https://user-images.githubusercontent.com/71358697/108325331-d4cd3100-717d-11eb-840b-62b951e12059.png)

![image](https://user-images.githubusercontent.com/71358697/108325298-cc74f600-717d-11eb-8d98-76c8288ffdec.png)
