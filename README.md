# CryptoClustering:
# the steps taken to complete the Cryptoclustering is :
imported the required library and dependency
loaded the csv data to the jupyter notebook for use and analysis.
the data was prepared using standardscaler to normalize the data from the csv file and found the best k value from the scaled datafram.i use the elbow method to find the optimal number of cluster.
the data is clusterd with k-means using the scaled datafram.

# optmized the clusters using PCA(principal component analysis);
the orginal dataframe is reduced to fewer feature to three principal component.
and also found the optimal number of cluster using elbow method from the pca data frame and found the best value of K-means.
*it also contrast the elbow curve from scaled datafram and pca dataframe  using composite plot for better understanding.
*it also contrast the elbow curve from scaled datafram and pca dataframe  using composite plot for better understanding.



# the following quesition is answered.
 * **Question:** After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

  * **Answer:** there is potential loss of information after using fewer feature to cluster.but,it less complex and faster computation at the expense of some accuracy