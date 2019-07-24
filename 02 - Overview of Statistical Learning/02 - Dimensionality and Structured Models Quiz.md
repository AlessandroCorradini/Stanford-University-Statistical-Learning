# Dimensionality and Structured Models Quiz

## 2.2 R1

A hypercube with side length 1 in d dimensions is defined to be the set of points (x1, x2, ..., xd) such that 0 <= x_j <= 1 for all j = 1, 2, ..., d. The boundary of the hypercube is defined to be the set of all points such that there exists a j for which 0 <= x_j <= 0.05 or 0.95 <= x_j <= 1 (namely, the boundary is the set of all points that have at least one dimension in the most extreme 10% of possible values). What proportion of the points in a hypercube of dimension 50 are in the boundary? (hint: you may want to calculate the volume of the non-boundary region)

Please give your answer as a value between 0 and 1 with 3 significant digits. If you think the answer is 50.52%, you should say 0.505:

The volume of the interior of the hypercube is 0.950 = 0.005. Thus, the volume of the boundary is 1-0.005 = **0.995**.
