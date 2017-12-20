Vector/Matrix Production Functions

Some concepts

**Outer Production:**
> The tensor product of two vectors *u* and *v*. This can be written as *uv*<sup>*T*</sup>. When the length of *u* is m and the length of *v* is n, the result of outer producting *u* and *v* is an m by n __matrix__ *w*, in which *w<sub>ij</sub>* = *u<sub>i</sub>* * *v<sub>j</sub>*

**Inner Production:**
> Or *__dot production__*. The summation of element-wise products of two equal-lengthed vectors. This can be written as *u*<sup>*T*</sup>*v*. The final result is a __scalar__. For example, *u* = (*u<sub>1</sub>*, *u<sub>2</sub>*, ... , *u<sub>n</sub>*), *v* = (*v<sub>1</sub>*, *v<sub>2</sub>*, ... , *v<sub>n</sub>*). Then *u* • *v* = Σ *u<sub>i</sub>* * *v<sub>i</sub>*

Some functions:

1. `numpy.outer`
Code:
**numpy.outer(*a*, *b*, *out*=*None*)**

Here, a and b are vectors. If not, they will be automatically flattened into the form of n x 1. The function calculates the outer production of vector a and b, then returns an `numpy.shape(a)` by `numpy.shape(b)` matrix. 

2. `numpy.dot`

3. `numpy.multiply`

4. `*`
