# Numerical math

## Topics

* Babylonian method **babylon.py**
* Bisection method **bisection.py**
* Regula falsi method **regulafalsi.py**
* Newton method **newton.py**
* Jacobi method **jacobi.py**
* Gauss Seidel method **gaussseidel.py**
* Lagrange polynomial **lagrange.py**
* Least squares method **leastsquares.py**
* Numerical integration - Rectangular method **rectangle.py**
* Numerical integration - Trapezoidal method **trapezoid.py**

## How to

### Running

First insert the numa package to your PYTHONPATH. This is example on how to run the babylon.py script.

    cd numa/topics && python babylon.py

### Functions

Python         | Sympy expression
-------------- | ----------------
math.log(x)    | log(x)
math.log10(x)  | log10(x)
math.exp(x)    | exp(x)
math.sin(x)    | sin(x)
math.cos(x)    | cos(x)

### Matrices and Vectors

```python
# input matrices as lists
[[11,2,1],[1,10,2],[2,3,-8]]

# it will generate this Matrix instance
Matrix((
    [11,2,1],
    [1,10,2],
    [2,3,-8]
))

# input vectors as lists
[15, 16, 1]
```