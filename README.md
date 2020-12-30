## K-Means clustering unsupervised learning algorithm
I have used Mini-Batch K-Means, to compress images, and leveraged the Jupyter widgets library to build interactive GUI component to select images from a drop-down list and pick values of k using a slider.

![Alt text](images_github/Kmeans_animation.gif?raw=true "Title")

MiniBatchKMeans reduces the convergence time of the k-means algorithm by using randomly sampled subsets (mini-batches) of the input data in each interation.

![Alt text](images_github/algo.png?raw=true "Title")

Each observation is assigned to a cluster based on which cluster center is closest to it, based on the euclidean distance.