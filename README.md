# Homework_week10

This homework aims to cluster cryptocurrencies using the K-means algorithm, both with the original data and optimised clusters with Principal Component Analysis (PCA). The steps include importing and preparing data, identifying the optimal 'k' value for the clustering algorithm, and performing PCA to optimize the cluster analysis.

## Steps to Follow
### Import and Prepare the Data: Utilize the starter code provided to complete this task.

Find the Best Value for k Using the Original Data: Apply the elbow method to find the best value for 'k'. This involves coding the elbow method algorithm and plotting a line chart for inertia values against varying 'k' values.

Cluster Cryptocurrencies with K-means Using the Original Data: Use the K-means algorithm to cluster the cryptocurrencies. Initialise and fit the K-means model, predict the clusters, create a copy of the original data with the predicted clusters, and visualise the results using a scatter plot.

Optimise Clusters with Principal Component Analysis (PCA): Perform PCA to reduce the features to three principal components. Review the total explained variance, create a DataFrame with PCA data, and use this for the next step.

Find the Best Value for k Using the PCA Data: Similar to step 2, apply the elbow method to find the optimal 'k' value but this time, use the PCA data.

Cluster Cryptocurrencies with K-means Using the PCA Data: Similar to step 3, use the K-means algorithm to cluster the cryptocurrencies but this time, use the PCA data. Visualise the results using a scatter plot.

Visualise and Compare the Results: Analyse the cluster analysis results visually. Create composite plots to compare the elbow curve (for best 'k' value) and the cryptocurrency clusters using the original data and PCA data.
