**Section2: Datastructures for Algebra**


- Algebra is arithmetic that includes non numerical entities like x:
    e.g. 2x+5 = 25

- if it has an exponential term, it isn't linear algebra. e.g:
    2x^2 + 5 =25


In a given system of equations:
* Could be many equations.
* Could be many unknown in each equation.

y = a + bx1 + cx2 + ..... + mxm

y1 | a + bx11 + cx12 + ..... + mx1m
y2 | a + bx21 + cx22 + ..... + mx2m
y3 | a + bx31 + cx32 + ..... + mx3m
y4 | a + bx41 + cx42 + ..... + mx4m
 . |         .       .         . .
yn | a + bxn1 + cxn2 + ..... + mxnm


Tensors: ML gnereralization of vector and matrices to any number of dimensions
scaler x,
vector [x1, x2, x3], 
matrix [[x1, x2, x3],[y1, y2, y3]]


Orthogonal Vectors
- x and y are orthogonal vectors if x^T.y = 0
- Are at 90 angle to each other (assuming non-zero norms)
- n-dim space has max n mutually orthogonal vectors (again, assuming non zero norms)
- Orthonormal vectors are orthogonal and all have unit norm
    - Basis vectors are an example i= (1, 0) and j = (0, 1)