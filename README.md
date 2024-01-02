# Predicting-Titanic-Survivor-Using-Titanic-Dataset
This program uses the K-Means Algorithm to classify people based on some metrics whether they survived the Titanic shipwreck or not. It uses K-Means Algorithm using Scikit Learn.

K-Means falls under Flat Clustering. In Flat Clustering, the user defines how many clusters he/she wants and the machine clusters accordingly.
Its a simple algorithm. The only parameter to be passed is the value of K, which is the number of clusters to be passed onto the machine. 

The Algorithm works as follows - 
    First we determine how many clusters we want. That is, what should be the value of K.
    Suppose K=n. Then, we need to choose randomly(recommended) exactly n centroids from among the data point given.
    Then, for each other points, we calculate its Euclidean distance from these n centroids and the classify it to the             group of that centroid to which its nearest to.
    Then we calculate the mean centroid for each cluster and find the new n centroids and repeat the process all over             again. We continue this until the centroids are no longer moving. Finally then, we have got our cluster.

In this algorithm, there will be some sort of tolerance and max iteration present.

The main issue with k-means is that it tries to create clusters of same size. Hence sometimes there might be difficulties to find clusters of same size and that might cause some errors in the output.

Here, in this code, we use the Titanic dataset and with the different metrics on the passengers given, we try to train the K-Means model, and try to see, whether with the given factors/data, how accurately does the algorithm predict whether the passenger survived or not.
For example - the survival of the passenger might depend on their age, gender, class etc.
