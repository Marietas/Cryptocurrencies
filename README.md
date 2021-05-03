# Cryptocurrencies

## Overview

The aim of this project is to develop a study for an investment bank that is considering launching a new cryptocurrency investment portfolio. The study details include what cryptocurrencies are available for purchase and how they can be classified for this new line of investiment. For this project, I have applied unsupervised machine learning functions in order to group the cryptocurrencie on a clustering algorithm. 

## Resources
- Data Source: [Crypto_data.csv](https://github.com/Marietas/Cryptocurrencies/blob/main/Resources/crypto_data.csv)
- System: Python 3.7.1

## Results

After processing and cleaning the data the total of 532 different cryptocurrencies were available. From that, the following data could be obtained:
### Elbow Curve
Based on the data the Clustering Cryptocurrencies were obtained running the K-Means being K=4. This value represents the best value to running the unsupervised machine learning and identify the clusters of the cryptocurrencies. The following graph represent the output of this analysis.

![image](https://user-images.githubusercontent.com/76540704/116832911-993ee200-ab84-11eb-97c0-c5c73c78f46a.png)

### 3D- Scatter Plot
The 3D graph shows how different the cryptocurrencies are grouped together. This graph has been developed using the PCA algorithm in order to reduce the cryptocurrencies dimensions to three principal components.

![image](https://user-images.githubusercontent.com/76540704/116833196-c50e9780-ab85-11eb-9bd1-1c905fa1df28.png)

### 2D- Scatter Plot
The 2D graph has been created to shows the relationship between total coin supply and total coins mined.

![image](https://user-images.githubusercontent.com/76540704/116833337-89c09880-ab86-11eb-8986-cf33b9caed93.png)


## Summary

I have processed 532 cryptocurrencies running the K-means=4 to find their trends. Each group's characteristics was examined in order to assess its success and future value to the investment bank's clients. Clusters related to the amount of available coins vs the total number of mined coins can be seen in the 2d scatter plot. Different clusters are easily seen in the 3D scatter graph, which is distributed using three principal component variables.
