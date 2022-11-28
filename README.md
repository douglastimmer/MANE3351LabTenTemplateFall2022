# MANE 3351 - Manufacturing Engineering Analysis

## Laboratory 10 Assignment

### Assigned: November 28, 2022

### Due: December 7, 2022 (no late submissions)

---

## Learning Goals

1.  Use of linear algebra to implement linear regression, and
1.  Use of Python linalg module to solve linear algebra problems

## Problem Description

Linear regression is a statistical procedure to fit a line to data. There are several methods of implementing linear regression including linear algebra. In this lab, you will use linear algebra to solve a linear regression problem.

The linear algebra formulation of the regression problem is

$$
\mathbf{Y}=\mathbf{Z\beta}+\mathbf{\varepsilon}
$$

Where $\mathbf{Y}$ is a ($b\times 1$) vector containing the response variable values, $\mathbf{Z}$ is a ($n\times(r+1)$) matrix containing a column of ones and the values of the independent variables, $\mathbf{\beta}$ is a ($(r+1)\times 1)$) vector containing the parameters of value of the linear regression equation and $\mathbf{\varepsilon}$ is a ($n\times 1$) vector containing the error terms. $\mathbf{\varepsilon}$ is not observed.

The solution is given by

$$
\mathbf{\hat{\beta}}=\mathbf{\left(Z^\prime Z\right)^{-1}Z^\prime Y}
$$

The date for this laboratory is

$$
\mathbf{Y}=\left[\begin{matrix}9\\6\\9\\0\\2\\3\\1\\2 \end{matrix}\right]
$$

and 

$$
\mathbf{Z}=\left[\begin{matrix}
1 & 1 & 0&0\\
1&1&0&0\\
1&1&0&0\\
1&0&1&0\\
1&0&1&0\\
1&0&0&1\\
1&0&0&1\\
1&0&0&1\\
\end{matrix}\right]
$$



## Your Solution

### Cell 1

Update your personal information found in the first cell that is a Markdown cell.

### Cell 2

In cell 2 (code cell), enter the Python code using the linealg module to find the value of find the value of $\mathbf{\beta}$.

**Use GitHub Desktop to upload your repository when you have completed the Lab 10 Assignment.**