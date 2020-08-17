# K-Means-Clustering

### In this clustering task I have predicted the optimum number of clusters using Iris data and then visualised the clusters.

### This task was provided by The Sparks Foundation as a part of my Internship.

## K-Means Clustering

K-means clustering is a clustering method that subdivides a single cluster or a collection of data points into K different clusters or groups. 
The algorithm analyzes the data to find organically similar data points and assigns each point to a cluster that consists of points with similar characteristics.

#### Choosing the right number of clusters
The number of clusters that we choose for a given dataset cannot be random. Each cluster is formed by calculating and comparing the distances of data points within a cluster to its centroid. An ideal way to figure out the right number of clusters would be to calculate the Within-Cluster-Sum-of-Squares (WCSS).

#### Elbow Method
We can find the optimum value for K using an Elbow point graph. We randomly initialise the K-Means algorithm for a range of K values and will plot it against the WCSS for each K value.

### Libraries Required for the task
* Pandas
* matplotlib
* seaborn
* scikit-learn

### Data used
* Iris data

### Variables
* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

### Taarget Variable 
* Species
