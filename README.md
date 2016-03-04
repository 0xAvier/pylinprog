Linear Programming: Simplex Method
==================================

Pure python implementation of the [simplex method](https://en.wikipedia.org/wiki/Simplex_algorithm) solver for linear programming problem.

In short, it solves optimization problems of type:

    c1 x1 + c2 x2 + .... + cn xn -> min

    { a11 x1 + a12 x2 + .... + a1n xn <= b1
    { ...
    { am1 x1 + am2 x2 + .... + amn xn <= b1
	{ 
    { e11 x1 + e12 e2 + .... + e1n xn  = f1
	{ ...
    { ek1 x1 + ek2 e2 + .... + ekn xn  = f1


Current implementation does **not** uses dual problem method.
