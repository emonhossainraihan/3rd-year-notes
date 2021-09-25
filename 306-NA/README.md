## Differential Equations

### Runge-Kutta method

Runge-Kutta method here after called as RK method is the generalization of the concept used in Modified Euler's method.

In Modified Eulers method the slope of the solution curve has been approximated with the slopes of the curve at the end points of the each sub interval in computing the solution. The natural generalization of this concept is computing the slope by taking a weighted average of the slopes taken at more number of points in each sub interval. However, the implementation of the scheme differes from Modified Eulers method so that the developed algorithm is explicit in nature. The final form of the scheme is of the form:

```
yi+1  =  yi +  (weighted average of the slopes)
```

https://www.intmath.com/differential-equations/12-runge-kutta-rk4-des.php

https://web.mit.edu/10.001/Web/Course_Notes/Differential_Equations_Notes/node5.html

## Linear Systems

### Pivoting Strategies

https://www.youtube.com/watch?v=4YzIfcSFVCU

Norms, metrics, and other abstract concepts precisely express what closeness mean. we need sequences to converge with respect to certain norms.

https://math.stackexchange.com/questions/2028249/why-do-sequences-need-to-converge-with-respect-to-a-norm/2028277#2028277

**VECTOR NORM AND MATRIX NORM:** https://www.youtube.com/watch?v=MycsNMDvr_g

The Jacobi iterative method works fine with well-conditioned linear systems. If the linear system is ill-conditioned, it is most probably that the Jacobi method will fail to converge.
The Jacobi method can generally be used for solving linear systems in which the coefficient matrix is diagonally dominant.

The difference between the Gauss–Seidel and Jacobi methods is that the Jacobi method uses the values obtained from the previous step while the Gauss–Seidel method always applies the latest updated values during the iterative procedures.

A problem with a low condition number is said to be well-conditioned, while a problem with a high condition number is said to be ill-conditioned. In non-mathematical terms, an ill-conditioned problem is one where, for a small change in the inputs (the independent variables or the right-hand-side of an equation) there is a large change in the answer or dependent variable. This means that the correct solution/answer to the equation becomes hard to find.

Jacobi method does not converge
If the linear system is ill-conditioned, it is most probably that the Jacobi method will fail to converge. The Jacobi method can generally be used for solving linear systems in which the coefficient matrix is diagonally dominant.

https://math.stackexchange.com/questions/1607530/how-do-i-find-optimal-%CF%89-for-sor-method

## Eigenvalue estimate

[Gershgorin Circle Theorem to estimate the eigenvalues](https://scicomp.stackexchange.com/questions/1801/gershgorin-circle-theorem-to-estimate-the-eigenvalues)

https://www.lem.ma/books/BpCFAP27bgq6U3D-ympsug/landing

[Gershgorin circle theorem and similarity transformations](https://math.stackexchange.com/questions/3517040/gershgorin-circle-theorem-and-similarity-transformations/)

[How to prove a tighter bound for an eigenvalue of A with Gerschgorin's theorem and similar matrices](https://math.stackexchange.com/questions/3721084/how-to-prove-a-tighter-bound-lambda-3-1-leq-epsilon2-for-an-eigenvalue-o)

http://web.mit.edu/18.06/www/Spring17/Power-Method.pdf

https://www.mpp.mpg.de/~jingliu/ECPI/PowerMethodProof.pdf

Gershgorin Circle Theorem to estimate the eigenvalues: https://scicomp.stackexchange.com/a/1804

To get good bounds for a general matrix, one must compute an approximate eigensystem and then express the matrix in this basis by a simiarity transform. This doesn't change the eigenvalues but makes the off-diagonal entries small, so that the above applies.

## Schur decomposition

- http://web.math.ucsb.edu/~padraic/ucsb_2013_14/math108b_w2014/math108b_w2014_lecture5.pdf

## Projection onto a subspace

- https://math.stackexchange.com/questions/4198263/projection-on-to-a-subspace-and-orthogonal-basis-confusion?rq=1

## Nice Book

- https://engcourses-uofa.ca/books/numericalanalysis/
- https://rosettacode.org/wiki/QR_decomposition
- https://ocw.mit.edu/courses/mathematics/18-330-introduction-to-numerical-analysis-spring-2012/lecture-notes/

## Visualization of QR method

- https://www.youtube.com/watch?v=d-yPM-bxREs
