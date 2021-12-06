# FiniteDifference

Three Numerical differentiations for unkown function:
1. Forward Finite Difference
2. Central Finite Difference
3. Backward Finite Difference

Case A:
Input: (x,y,neighbor)
Output: diff of y with respect to x 

Case B:
Input: (y,neighbor)
Output: diff of y with respect to integer


The variable "neighbor" is used to determine how many data points are used to calculate the differentiations.
The default of "neighbor" is 1.
The Central Finite Difference Method is recommended to get better accuracy.

NOTE: When "neighbor" becomes larger, the curve will be smoother, but the boundary error will also be larger.
