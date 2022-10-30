# Cryptocurrencies
## Overview of the Module 18 Challenge

A company wants to invest in cryptocurrencies and needs the data to be filtered and grouped (tradable cryptocurrencies) to create a classification system. In order to achieve this, we performed data preprocessing to the crypto_data.csv file. This allowed us to convert all of our data to numbers in order to fit the data into the unsupervised machine-learning models. 

### Files and Folders

crypto_clustering.ipynb

Resources: images

## Results

The next processes were performed in order to arrive at the final results. 

### 1. Data transformation

We used Pandas properties and functions in order to clean and make our data transformation (loc, dropna, drop, join, get_dummies). We used StandardScaler to scale all of our data. 

!['1']()

### 2.  Reducing Data Dimensions and Clustering

We used the PCA function to reduce our dimensions to three. Then, we created an elbow curve to determine the optimal cluster number for our model. We created the model with KMeans and four clusters and finally, we added it into a DataFrame called clustered_df. 

!['2']()

### 3. Visualizing the results

We plotted in 3D the PCA components and the clusters (class) to see how the cryptocurrencies are grouped. We can see the 4 classes and classes 1 (purple) and 2 (blue) have the most number of cryptocurrencies. 

!['3']()

### Summary

Overall, we found that the data can be classified into 4 clusters. This is a pretty good starting point for understanding the general behavior of cryptocurrencies. Further analysis can be done into supervised machine learning to decide which ones would be the best to invest in.
