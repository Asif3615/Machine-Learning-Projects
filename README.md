# Machine-Learning-Projects

Project : "Clustering Income Spent using K - means Clustering"
The aim of this project is to Categorizing the information based on Amount Spent by using K - means Clustering['UNSUPERVISED LEARNING']. So I have used elbow method and inertia which is used to find out the best k value [A good model is one with low inertia and a low number of clusters].

Steps for finding values:
Step 1: Select the number of k to decide the number of clusters.
Step 2: Select random points or centroids.
Step 3: Calculate the distance between points[here we will use Euclidean Distance]. So we will draw a median between both centroid.
Step 4: To find the closest cluster, so we will repeat the process by choosing a new centroid.
Step 5: Reassign each datapoint to new centroid.
Step 6: As reassignment has taken place, so we will again go to the Step 4 , which is finally the new centroids or k-points.
Step 7: As we got the new centroids, so again will draw median line and reassign the data points.
Step 8: There are no. dissimilar data points on either side of line , which means our model is formed.

Project : "Clustering Income Spent Using Hierarchical Clustering "
The aim of this project is to Categorizing the information based on Amount Spent by using Hierarchical Clustering.
Methods :
1 - Compute a distance matrix by using Euclidean Distance
2 - Linkage criteria
(i) - ward : This method works out which observation to group based on reducing the sum of square distance of each observation from the average observation in a cluster.
3 - Types:
(i) Agglomerative Hierarchical Clustering (that I have used in my project) : Sequentially merging similar cluster
(ii) Divisive Hierarchical Clustering
Steps:
1 - Identity the two cluster that are closest
2- Merge the two must similar clusters.


Project : "Clustering Plant Iris Using Principal Component Analysis"
The aim of this project is to Categorizing Iris Data by using Principal Component Analysis. The main work of PCA is to reduce the dimensionality of large dataset, by transforming a large set of variables into a smaller one that still contain most of the information in the large set.
The Steps that are used to find out the variance percentage:
Step 1: Standardization
Z = value - mean / standard deviation
All the variables need to be transformed to same scale
Step 2: Covariance
How the variables of the input data are varying from the mean with respect to each other - Relationship between each other feature
Condition:
COORELATED: (+ve): Two variables increases or decreases together.
INVERSLY COORELATED: (-ve) One increases when the other decreases.
Step 3: Eigen values and Eigen Vectors
To find the Principle Component , EG and EV need to be computed on the covariance matrix.
- PRINCIPLE COMPONENTS -EIGEN VECTOR - EIGEN VALUES
Step 4: Feature Vector [DIMENSIONALITY REDUCTION]
To choose whether to keep all these components or discard those of lesser eigen values to form matrix with remaining ones-feature vector.
Step 5: Recasting Data along the axes of Principle Components.
PCA FORMULA :
Final Dataset = feature vector * Standardized Original Dataset


Project : "Movie Recommendation System using SVD"
The aim of this project is to identifying similar movies.
The Recommendation system contain 2 types which are:
1- Content Based Filtering:
It is based on a description of the item.
2- Collaborative Filtering
The people who have liked on item in the past will also like the same in future. This approach builds a model based on the past behaviour
of users. The user behaviour may include previously watched videos purchased items, given rating on items.
Algorithm: Singular Value Decomposition
