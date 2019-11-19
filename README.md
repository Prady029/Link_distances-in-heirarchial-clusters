# Link_distances-in-heirarchial-clusters
## A humble attempt to code the 4 types of distances used in heirarchial clustering. 
1. Single-link
2. Complete-link
3. Average-link
4. Centroid-link

## All feedbacks are appreciated :)

# The theory behind:
## MIN or Single Link
- The distance between two clusters is represented by the distance of the closest pair of data objects belonging to different   clusters.
-	Determined by one pair of points, i.e., by one link in the proximity graph

## MAX or Complete Link
-	The distance between two clusters is represented by the distance of the farthest pair of data objects belonging to different clusters.

## Group Average or Average Link
-	The distance between two clusters is represented by the
 average distance of all pairs of data objects belonging to different clusters
-	Determined by all pairs of points in the two clusters
-	Compromise between Single and Complete Link

## Centroid Distance
-	The distance between two clusters is represented by the distance between the centers of the clusters
-	Determined by cluster centroids
