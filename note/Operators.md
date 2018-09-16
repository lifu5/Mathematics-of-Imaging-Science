# Types of Operators

### Functions and functionals

A function f(x) is a transformation or mapping from one linear vector space to another. an example f(x) = x^2, the domain is R1(-infty, infty) and the range is R1[0,infity)

By contrast, a functional is a mapping from a function space to scalar. for functional, its input is the function and output is a scalar.

**Duality**

the mapping (function):  x0 -> f(x0)  from vector space to R  
the funtional:   f -> f(x0)   from a function space to R

**linear functional**

<a href="https://www.codecogs.com/eqnedit.php?latex=\Phi&space;(f_1(x)&plus;cf_2(x))&space;=&space;\Phi(f_1(x))&plus;c\Phi(f_2(x))" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\Phi&space;(f_1(x)&plus;cf_2(x))&space;=&space;\Phi(f_1(x))&plus;c\Phi(f_2(x))" title="\Phi (f_1(x)+cf_2(x)) = \Phi(f_1(x))+c\Phi(f_2(x))" /></a>

According to *Riesz Representation Theorm* the most general form of a linear functional on a Hilbert Space is a scalar product of the form <a href="https://www.codecogs.com/eqnedit.php?latex=\Phi&space;(f(x))&space;=&space;<a,f>&space;=&space;\int&space;a^*(x)f(x)&space;dx" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\Phi&space;(f(x))&space;=&space;<a,f>&space;=&space;\int&space;a^*(x)f(x)&space;dx" title="\Phi (f(x)) = <a,f> = \int a^*(x)f(x) dx" /></a>

Not every functional is linear. A simple example is the norm for linear function.

-----
### Integral transforms

A mapping from function to function we call integral transforms.

The general form of a linear intgral transform connectiong 1D function is <a href="https://www.codecogs.com/eqnedit.php?latex=g(x')&space;=&space;\int_{\alpha}^{\beta}&space;dx\&space;h(x',x)f(x)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?g(x')&space;=&space;\int_{\alpha}^{\beta}&space;dx\&space;h(x',x)f(x)" title="g(x') = \int_{\alpha}^{\beta} dx\ h(x',x)f(x)" /></a>

where h is called the kernel of the transform. 

!! A  linear integral transform from L2R to L2R if both f and h are square-integrable

another example of a linear transform g(x) = \intgral f(x,y) dy (from L2R2 to L2R1) and f(x,y) are square-integrable in their respective spaces

-----
### Continuous-to-discrete mappings

<a href="https://www.codecogs.com/eqnedit.php?latex=g_m&space;=&space;\int_{\alpha}^{\beta}dx\&space;f(x)h_m(x)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?g_m&space;=&space;\int_{\alpha}^{\beta}dx\&space;f(x)h_m(x)" title="g_m = \int_{\alpha}^{\beta}dx\ f(x)h_m(x)" /></a>

!! keep square-integrable in mind when consider range and domain!!