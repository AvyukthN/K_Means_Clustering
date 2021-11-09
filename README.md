### K-Means Image Clustering

This is a general K-Means algorithm implemented from scratch in python purposed for image clustering

**K-Means Clustering**: K-Means is an unsupervised machine learning clustering algorithm that can seperate data points into clusters.

**Step 1**
First picks k random points are chosen from the dataset depending on how many clusters the user desires

**Step 2**
Data points from the dataset are then sorted according to which of the k random points they are closest to (euclidian distance was used in this implementation but also can be used for any multidimensional vector space)

**Step 3**
The average of the datapoints in each category is taken and the averages become the new categories.

**Step 4**
The datapoints in the dataset are resorted according to which category they are closest to similar to step 2. This step is repeated until none of the datapoints switch categories, and at that point K-Means is complete, the datapoints in k seperate categories constitute the k clusters found and the centroids for these categories are the categories themselves.