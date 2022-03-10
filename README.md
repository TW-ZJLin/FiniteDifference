# FiniteDifference

## Introduction
Three Numerical differentiations for unkown function:
1. Forward Finite Difference
2. Central Finite Difference
3. Backward Finite Difference

## input/output format
Case A:<br>
* Input: ( x, y, neighbor ) <br>
  * x, y: Numpy array with 1 dimensions <br>
  * neighbor: integer <br>
* Output: ( y_diff ) <br>
  * y_diff: Numpy array with 1 dimensions ( differentiations of y with respect to x ) <br>

Case B:<br>
* Input: ( x, neighbor ) <br>
  * x: Numpy array with 1 dimensions <br>
  * neighbor: integer <br>
* Output: ( x_diff ) <br>
  * x_diff: Numpy array with 1 dimensions ( differentiations of x with respect to natural number ) <br>

>The variable "neighbor" is used to determine how many data points are used to calculate the differentiations. <br>
The default of "neighbor" is 1. <br>
The Central Finite Difference Method is recommended to get better accuracy. <br>

NOTE: When "neighbor" becomes larger, the curve will be smoother, but the boundary error will also be larger.<br><br>

## Sample
Analytic Expression: <br>
The function is y = 12*x**3 + 15*x**2 - 20*x + 8 <br>
![](https://github.com/TW-ZJLin/FiniteDifference/blob/main/analytic_expression.png)<br>
Results: <br>
![](https://github.com/TW-ZJLin/FiniteDifference/blob/main/results.png)
