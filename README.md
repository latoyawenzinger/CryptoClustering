# CryptoClustering


This assignment uses two unsupervied machine learning techniques to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. Both technioques are compared to deteremine if there is an impact of using fewer features to cluster data using KMeans. 

**TECHNIQUE 1**:

  -- Use StandarScaler() to normalize the data
  -- Find the best value for k using original data
  -- Fit the K-means model by using the original data
  -- Predict the clusters
  -- Create a scatter plot using hvPlot clustered appropriately 
  
  **TECHNIQUE 2**:
  -- Use Principal Component Analysis (PCA) reduce the features to three principal components
  -- Calculate total explained variance of the three features
  -- Find the best value for k 
  -- Fit the K-means model
  -- Predict the clusters
  -- Create a scatter plot using hvPlot clustered appropriately 
