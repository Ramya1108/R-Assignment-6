A=matrix(c(2,0,1,3), ncol=2)
B=matrix(c(5,2,4,-1),ncol=2)
 A + B
 A - B
p=diag(c(4,1,2,3),nrow=4,ncol=4)
R=matrix(c( 3,1,1,1,1,2,3,0,0,0,2,0,3,0,0,2,0,0,3,0,2,0,0,0,3),nrow=5,ncol=5)
View(R)


Explanation

1)Matrix A and Matrix B Initialization:
 A <- matrix(c(2, 0, 1, 3), ncol = 2): Creates a 2x2 matrix A with elements (2, 0, 1, 3).
B <- matrix(c(5, 2, 4, -1), ncol = 2): Creates a 2x2 matrix B with elements (5, 2, 4, -1).

2)Matrix Addition and Subtraction:
A + B: Performs element-wise addition of matrices A and B.
A - B: Performs element-wise subtraction of matrices A and B.

3)Diagonal Matrix Creation:
p <- diag(c(4, 1, 2, 3), nrow = 4, ncol = 4): Creates a 4x4 diagonal matrix p with diagonal elements (4, 1, 2, 3).

4)Matrix R Initialization:
R <- matrix(c(...), nrow = 5, ncol = 5): Creates a 5x5 matrix R with the provided values arranged in row-major order.
The values are arranged in such a way that the diagonal elements are all 3, and certain off-diagonal elements have values of 2, 1, or 0.

5)Viewing Matrix R:
View(R): Opens a data viewer window to display the matrix R
