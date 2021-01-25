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
