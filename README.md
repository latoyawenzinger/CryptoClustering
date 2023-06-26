# CryptoClustering


This assignment uses two unsupervised machine learning techniques to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. Both techniques are compared to determine if there is an impact of using fewer features to cluster data using KMeans. **Principal Component Analysis (PCA)** is an optimizing machine learning method that reduces large datasets into smaller ones. Eventhough the datasets are reduced, it still preserves most on the information. 

**TECHNIQUE 1**:

    - Use StandarScaler() to normalize the data
    - Find the best value for k using original data
    - Fit the K-means model by using the original data
    - Predict the clusters
    - Create a scatter plot using hvPlot clustered appropriately 
  
  **TECHNIQUE 2**:
  
    - Use PCA to reduce the features to three principal components
    - Calculate total explained variance of the three features
    - Find the best value for k 
    - Fit the K-means model
    - Predict the clusters
    - Create a scatter plot using hvPlot clustered appropriately 
    

**Analysis:**

- Although 2 different techniques were used to find the optimal k value, both elbow curves were similar and produced the same value of 4

![image](https://user-images.githubusercontent.com/115582691/235747943-00b9a8c5-d2cc-463c-97ae-3bc207916bbe.png)


- Plot one displays cluserting of the original data
- Plot two displays clustering of the data being reducing to 3 features

![image](https://user-images.githubusercontent.com/115582691/235753603-b3a1438e-6262-4ba8-aa03-55d7fa0dd4cb.png)
![image](https://user-images.githubusercontent.com/115582691/235753676-4ca1f120-ea8e-4018-aded-436fd5dc3ac4.png)
