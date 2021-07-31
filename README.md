# Cryptocurrencies

## Purpose

The purpose of this project is to analyze various cryptocurrencies for a prominent investment bank looking to offer a new crypto investment portfolio to its customers. To group the various cryptocurrencies, I used unsupervised machine learning with a clustering algorithm to create a classification system on data provided by CryptoCompare. Results are then presented in the data frames and data visualizations provided below. 

## Steps

- Preprocessed the data using Pandas in order to perform principle component analysis (PCA)
- Reduced data dimensions to three principal components using the PCA algorithm
- Clustered the cryptocurrencies using the K-means alogrithm to predict the K clusters 
- Visualized the results with Plotly Express and hvplot to show the distinct groups that correspond to the three principal components

## Results
![Tradable_Crytpo_DataFrame](https://github.com/tysonseang/Cryptocurrencies/blob/main/Resources/Tradable_Crypto_DataFrame.png)
![3D_Scatter_With_Clusters](https://github.com/tysonseang/Cryptocurrencies/blob/main/Resources/3D_Scatter_With_Clusters.png)
![Final_DataFrame](https://github.com/tysonseang/Cryptocurrencies/blob/main/Resources/Final_DataFrame.png)
![Scatter_Plot](https://github.com/tysonseang/Cryptocurrencies/blob/main/Resources/Scatter_Plot.png)