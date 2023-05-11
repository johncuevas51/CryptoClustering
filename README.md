# CryptoClustering
Module_19_challenge

This project utilizes K-Means clustering to group cryptocurrencies. It includes a comparison of clustering results obtained from the original data and the principal component analysis (PCA) data. The implementation involves Python and popular data science libraries such as scikit-learn, pandas, and hvPlot. These tools are used to prepare and analyze the data, visualize the clustering results, and extract valuable insights from the analysis.

Key steps/processes of assignment

StandardScaler --
Used the StandardScaler() module from scikit-learn to normalize the data from the CSV file.
Created a dataframe with the scaled data and se the coin id index as new index for new dataframe. 

Elbow method-- best value for both original scaled data and PCA data is 4.
used to find best value for k

Principal Component Analysis (PCA)-- used to optimize the clusters to 3.
Answer the following question:
Question: What is the total explained variance of the three principal components?

Answer: total explained variance is 89.5%

Plot a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k.
Question : What is the best value for k? answer 4

Comparison:
Answer the following question:
Question: After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

Answer: after visually analyzing, the elbow curves are similar. Scatter plots -- after applying PCA, the scatter is more cleaner.

Elbow Curve Comparison :
Elbow Curve 1
![Screen Shot 2023-05-11 at 3 14 01 PM](https://github.com/johncuevas51/CryptoClustering/assets/119380122/249f64b8-3111-45a1-8c8e-22caf09616d9)

Elbow Curve 2 with PCA
![Screen Shot 2023-05-11 at 3 14 39 PM](https://github.com/johncuevas51/CryptoClustering/assets/119380122/0be4f30e-db74-495f-9ff2-a3f665d73ebe)

Scatter Plot Comparison : 
Scatter 1
![Screen Shot 2023-05-11 at 3 14 54 PM](https://github.com/johncuevas51/CryptoClustering/assets/119380122/0b50806c-6cce-4ab1-a147-f5760d8f26eb)

Scatter 2- with PCA

![Screen Shot 2023-05-11 at 3 15 18 PM](https://github.com/johncuevas51/CryptoClustering/assets/119380122/683498a6-0421-4179-9c0b-68801f3deb06)


Technologies and Methods Used
Python
Scikit-learn
Pandas
hvPlot
K-Means clustering
StandardScaler
Principal Component Analysis (PCA)
Elbow method
