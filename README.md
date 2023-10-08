# CryptoClustering

# Data Preparation
1. Used the StandardScaler() module from scikit-learn to normalize the data from the CSV file.
2. Created a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.
# Original Scaled Data
1. Found the Best Value for k Using the Original Scaled DataFrame using the elbow method.
2. What is the best value for k? The best value of k was 4
3. Clustered Cryptocurrencies with K-means Using the Original Scaled Data
4. Created a scatter plot using hvPlot using x="price_change_percentage_24h" and y="price_change_percentage_7d". and coluring it by the clusters
# Optimising Clusters with Principal Component Analysis
1. Using the original scaled DataFrame, performed a PCA and reduced the features to three principal components.
2. Retrieved the explained variance to determine how much information can be attributed to each principal.
3. Created a new DataFrame with the PCA data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.
# PCA Data
1. Found the Best Value for k Using the  PCA data using the elbow method.
2. What is the best value for k? The best value of k was 4
3. Does it differ from the best k value found using the original data? No.
4. Clustered Cryptocurrencies with K-means Using the PCA Data
5. Created a scatter plot using hvPlot using x="PCA1" and y="PCA2". and coluring it by the clusters.
# Question
What is the impact of using fewer features to cluster the data using K-Means? 
# Answer
The clusters are well defined. Less overlap bewteen clusters.
# Composite Plots.
Created composite plots of the elbow data and the clustered data of the original scaled data and PCA data respectively to visualise differences of using lesser feautures 
to cluster Data using KMeans.

