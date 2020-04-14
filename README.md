# K-Means

Clustering

Clustering is one of the most common exploratory data analysis technique used to get an intuition about the structure of the data. It can be defined as the task of identifying subgroups in the data such that data points in the same subgroup (cluster) are very similar while data points in different clusters are very different. In other words, we try to find homogeneous subgroups within the data such that data points in each cluster are as similar as possible according to a similarity measure such as euclidean-based distance or correlation-based distance.

Clustering analysis can be done on the basis of features where we try to find subgroups of samples based on features

Kmeans Algorithm

Kmeans algorithm is an iterative algorithm that tries to partition the dataset into Kpre-defined distinct non-overlapping subgroups (clusters) where each data point belongs to only one group. It tries to make the inter-cluster data points as similar as possible while also keeping the clusters as different (far) as possible. It assigns data points to a cluster such that the sum of the squared distance between the data points and the cluster’s centroid is at the minimum.

kmeans algorithm works is as follows:

1.Choose value for K

2.Randomly select K featuresets to start as your centroids

3.Calculate distance of all other featuresets to centroids

4.Classify other featuresets as same as closest centroid

5.Take mean of each class (mean of all featuresets by class), making that mean the new centroid

6.Repeat steps 3-5 until optimized (centroids no longer moving)

