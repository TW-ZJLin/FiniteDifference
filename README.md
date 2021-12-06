# FiniteDifference

Three Numerical differentiations for unkown function:
1. Forward Finite Difference
2. Central Finite Difference
3. Backward Finite Difference

Case A:<br>
Input: (x,y,neighbor)<br>
Output: differentiations of y with respect to x <br>

Case B:<br>
Input: (y,neighbor)<br>
Output: differentiations of y with respect to integer<br>


The variable "neighbor" is used to determine how many data points are used to calculate the differentiations. <br>
The default of "neighbor" is 1. <br>
The Central Finite Difference Method is recommended to get better accuracy. <br>

NOTE: When "neighbor" becomes larger, the curve will be smoother, but the boundary error will also be larger.<br><br>

Results: <br>
![](https://github.com/TW-ZiJieLin/FiniteDifference/blob/main/results.png)
