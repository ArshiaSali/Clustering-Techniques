# Clustering-Techniques

The notebook demonstrates various Clustering Techniques like
- DBSCAN
   - Density-based spatial clustering of applications with noise (DBSCAN) is a data clustering algorithm.
   -  It is a density-based clustering non-parametric algorithm: given a set of points in some space, it groups together points that are closely packed together (points with many nearby neighbors), marking as outliers points that lie alone in low-density regions (whose nearest neighbors are too far away). 
   -  DBSCAN is one of the most common clustering algorithms and also most cited in scientific literature.
- GMM
   - Gaussian mixture models (GMMs) are often used for data clustering. GMMs can be used to perform either hard clustering or soft clustering on query data. 
   - To perform hard clustering, the GMM assigns query data points to the multivariate normal components that maximize the component posterior probability, given the data.
- KMEANS
   - K-Means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster. This results in a partitioning of the data space into Voronoi cells. 
   - K-Means clustering minimizes within-cluster variances (squared Euclidean distances), but not regular Euclidean distances, which would be the more difficult Weber problem: the mean optimizes squared errors, whereas only the geometric median minimizes Euclidean distances. For instance, better Euclidean solutions can be found using k-medians and k-medoids.
- HIERARCHIAL CLUSTERING
    Hierarchical Clustering (also called hierarchical cluster analysis or HCA) is a method of cluster analysis which seeks to build a hierarchy of clusters. 
    
    Strategies for hierarchical clustering generally fall into two types:

    - Agglomerative: This is a "bottom-up" approach: each observation starts in its own cluster, and pairs of clusters are merged as one moves up the hierarchy.
    
    - Divisive: This is a "top-down" approach: all observations start in one cluster, and splits are performed recursively as one moves down the hierarchy.

Comparison of the above algorithms and the Inferences are also recorded in the notebook.

## Dataset

The dataset for this demonstartion is available here
<a href="https://drive.google.com/drive/folders/1G1rauqKLVSSB_V36ufYl4zD2xan6bZuR?usp=sharing">DATASET</a>
