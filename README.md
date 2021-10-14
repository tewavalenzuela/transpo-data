# transpo-data
OICA(International organization of motor vehicle manufacturers) is the voice speaking 
on automotive issues in world forums. OICA 2017 production statistics, being the basis of transpo-data project, eradicate the 
unwanted information and catalogues the useful data in an effortless way making the 
humongous task of orgazising inputs seem to furtile and serene.

## k Means Clustering Algorithm
The type of data best suited for K-Means clustering would be numerical data with a relatively lower number of dimensions. A reasonably intuitive way of thinking about the problem is that there are really two things we ask of our clusters: homogeneity (things in the same cluster should all look like each other) and separation (things in different clusters should look different from each other).

![download (2)](https://user-images.githubusercontent.com/92322030/137151607-22c5608c-bec5-40ef-a4ad-b6421c2b186d.png)

## Inertia and Elbow Method
Inertia is the sum of squared distance of samples to their closest cluster center. The value of inertia decreases as the number of clusters increase- so we will need to manually pick K while considering the trade-off between the inertia value and the number of clusters. For that, we usually use the Elbow Method- and we choose the elbow point in the inertia graph

![download](https://user-images.githubusercontent.com/92322030/137150915-75b68099-4723-4f41-84fe-23dfade11ede.png)
