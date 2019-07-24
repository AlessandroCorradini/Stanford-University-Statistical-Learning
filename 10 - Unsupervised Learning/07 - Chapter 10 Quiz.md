# Chapter 10 Quiz

## 10.Q.1

K-Means is a seemingly complicated clustering algorithms. Here is a simpler one:

Given k, the number of clusters, and n, the number of observations, try all possible assignments of the n observations into k clusters. Then, select one of the assignments that minimizes Within-Cluster Variation as defined on page 30.

Assume that you implemented the most naive version of the above algorithm. Here, by naive we mean that you try all possible assignments even though some of them might be redundant (for example, the algorithm tries assigning all of the observations to cluster 1 and it also tries to assign them all to cluster 2 even though those are effectively the same solution).

In terms of n and k, how many potential solutions will your algorithm try?

**k^n**
