# Module-6-Doing-math-in-R-part-2


Paper View
 

#a) Find A + B
#b) Find A - B

> A <- matrix(c(2,0,1,3), ncol = 2)
> B <- matrix(c(5,2,4,-1), ncol=2)
> sumAB <- A + B
> sumAB
     [,1] [,2]
[1,]    7    5
[2,]    2    2
> difAB <- A - B
> difAB
     [,1] [,2]
[1,]   -3   -3
[2,]   -2    4

#Using the diag() function to build a matrix of size 4 with the following values in the diagonal 4,1,2,3.
> exDiag <- diag(c(4, 1, 2, 3), ncol = 4)
> exDiag
     [,1] [,2] [,3] [,4]
[1,]    4    0    0    0
[2,]    0    1    0    0
[3,]    0    0    2    0
[4,]    0    0    0    3
> x <- c(3, 1, 1, 1, 1)
> y <- c(3, 2, 2, 2, 2)
> d <- c(3, 3, 3, 3, 3)
> exDiag2 <- diag(d)
> exDiag2[1,] <- x
> exDiag2[,1] <- y
> exDiag2

#Generation of the matrix:
     [,1] [,2] [,3] [,4] [,5]
[1,]    3    1    1    1    1
[2,]    2    3    0    0    0
[3,]    2    0    3    0    0
[4,]    2    0    0    3    0
[5,]    2    0    0    0    3
> save.image("C:\\Users\\rushi\\Downloads\\module 6 R")
