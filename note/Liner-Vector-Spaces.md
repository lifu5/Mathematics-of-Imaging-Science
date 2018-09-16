# Linear Vector Spaces #

Let us define a linear vector space, in which the operations of addition and multiplication by scalar are defined and satisfy the following nine conditions.

1.  <a href="https://www.codecogs.com/eqnedit.php?latex=(u&plus;v)\mathbf{f}&space;=&space;u\mathbf{f}&plus;v\mathbf{f}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?(u&plus;v)\mathbf{f}&space;=&space;u\mathbf{f}&plus;v\mathbf{f}" title="(u+v)\mathbf{f} = u\mathbf{f}+v\mathbf{f}" /></a> 
2. u(v**f**) = v(u**f**)
3. 1**f** = **f**
4. **f**1 +**f**2 = **f**2 + **f**1
5. ( **f**1+**f**2)+**f**3 = **f**1 +( **f**2 +**f**3)
6. u( **f**1 + **f**2) = u**f**1+u**f**2
7. **0** vector: 0**f** = **0**, **0**+**f** = **f**
8. Continuity of addition: if lim_n **f**n = **f** lim_n **g**n = **g**, then lim_n( **f**n+**g**n) = **f**+**g**, n-> infinite
9. Continuity of multiplication if ... then lim_n( **f**n**g**n) = **fg**

Now we define metric. The definition should satisfies three conditions.

1.  d( **f**1, **f**2) = d( **f**2, **f**1)
2.  d( **f**1, **f**2) >= 0
3.  d( **f**1, **f**2) = 0 iff f1 =f2
4.  triangle inequality

Norm, it satisfy

1. ||**f**|| >= 0 with equality iff **f**=0
2. ||u**f**|| = |u|*||**f**|| u is an arbitrary real or complex
3. triangle inequality

Usually we have L2 norm, L1 norm, Lp norm and L infinte norm (sup norm)

-----

Another important concept is limit of a sequnece of vectors and compelete metric spaces

 <a href="https://www.codecogs.com/eqnedit.php?latex=\lim&space;\limits_{n&space;\to&space;\infty&space;}&space;f_{n}&space;=&space;a" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\lim&space;\limits_{n&space;\to&space;\infty&space;}&space;f_{n}&space;=&space;a" title="\lim \limits_{n \to \infty } f_{n} = a" /></a>

A sequence of vector f_n in **metric space** converges the the fixed vector and ||f_n - a|| tends to zero.

```
Cauchy sequence: distance from **f**j to **f**k approaches zero as j and k go to infinity.

Every convergent sequence is a Cauchy sequence but the converse is not true.
```
Now we can define *complete* :

**if  the limit vector a is an element of the same space where the f_n is defined for every Cauchy sequence, then the space is said to be complete**

```
A complete normed linear space is called a Banach space
```

----
### Hilbert Space

Now we define **Scalar products**

the scalar or inner product (**f**1,**f**2) is a complex-valued functional of the vectors **f**1 and **f**2 with the following properties:

inner product: **H**x**H** --> **R**

1) (**f**1, **f**2) = (**f**2, **f**1)*;
2) (**f**1, a**f**2) = a(**f**1, **f**2) 
3) (a**f**1, a**f**2) = a*(**f**1, **f**2) 
4) (**f**1+**f**2, **f**3) = (**f**1, **f**3) + (**f**2, **f**3)
5)  (**f**1, **f**1) >= 0 with equality iff **f**1 is the zero vector

A Hilbert space is always normed with the norm ||f|| defined as <a href="https://www.codecogs.com/eqnedit.php?latex=\sqrt(f_1,f_1)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sqrt(f_1,f_1)" title="\sqrt(f_1,f_1)" /></a>
so that Hilbert spaces are Banach spaces.The coverse doese not hold, since not all norms are compatible with the required properties of scalar products. for example, L_p (p!=2)

add by Fu, In my view inner product is a stronger condition than norm

Now we can give two examples of Hilbert Space: &nbsp; A finite dimensional Eculidean space and the space L2(a,b) with a scalar product defined by <a href="https://www.codecogs.com/eqnedit.php?latex=^{\int_{\alpha}^{\beta&space;}f(x)_{1}^{*}f_{2}(x)dx}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?^{\int_{\alpha}^{\beta&space;}f(x)_{1}^{*}f_{2}(x)dx}" title="^{\int_{\alpha}^{\beta }f(x)_{1}^{*}f_{2}(x)dx}" /></a>
For the norm to exist, the integral over range(alpha, beta) must exist, so L2(a,p) is referred to as the space of square-inegrable functions.

```
add by Fu, in my view, we can regard a finite E^n as a continuous infinite function in range(alpha, beta), something like (x1,..., xN, 0,0,0,0,0), a vector in E^N corresponds to a mapping or function in range (a,b).
```
**weighted scalar products** can let us deal with functions that are not square-integrable themselves. the norm is defined by 
<a href="https://www.codecogs.com/eqßßnedit.php?latex=||f||_w&space;=&space;[\int_{\alpha}^{\beta}{dx\&space;w(x))|f(x)|^2)}]^{1/2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?||f||_w&space;=&space;[\int_{\alpha}^{\beta}{dx\&space;w(x))|f(x)|^2)}]^{1/2}" title="||f||_w = [\int_{\alpha}^{\beta}{dx\ w(x))|f(x)|^2)}]^{1/2}" /></a>

**Sobolev Space** 
weak derivatives??

----
### Basis vectors
- straightforward in E^N
- in L2 continuous  basis (orthogonal required)




