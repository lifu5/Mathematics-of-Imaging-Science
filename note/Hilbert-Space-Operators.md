# Hilbert Space Operators

Consider a linear operator <a href="https://www.codecogs.com/eqnedit.php?latex=\mathcal{H}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathcal{H}" title="\mathcal{H}" /></a> that maps a vector f in hilbert space U to a vetor g in the hilbert space V <a href="https://www.codecogs.com/eqnedit.php?latex=g&space;=&space;\mathcal{H}f" target="_blank"><img src="https://latex.codecogs.com/gif.latex?g&space;=&space;\mathcal{H}f" title="g = \mathcal{H}f" /></a>

**Linearity Boundeness and continuity**

- The operator <a href="https://www.codecogs.com/eqnedit.php?latex=\mathcal{H}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathcal{H}" title="\mathcal{H}" /></a> is linear if  ***H***[**f**1+c**f**2] = ***H*****f**1 + c***H*****f**2
- if there exists a positive Q  such that ||***H*****f**||< Q||**f**|| for all **f** in space U
- exists a & > 0 such that ||***H*** f1 - ***H*** f2||<e whenever ||**f**1 - **f**2|| < & 

**Compactness** 

a compact operator is one that maps a bounded sequence into one having a convergent subsequnce. More precisely whenever {**f**_j} is a sequence in U with ||**f**_j|| < C, then  {***H*****f**_j}  contains a convergent subsequence is ***H*** is compact.

The Hilbert-Schmidt theorem provides an important way of determining if an integral transform is compact. A linear intgral operator is compact if its kernel satisfies the condition 

<a href="https://www.codecogs.com/eqnedit.php?latex=\int_{\alpha}^{\beta}&space;dx&space;\int_{\alpha}^{\beta}&space;dx'|h(&space;x',x)|^2<&space;\infty" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\int_{\alpha}^{\beta}&space;dx&space;\int_{\alpha}^{\beta}&space;dx'|h(&space;x',x)|^2<&space;\infty" title="\int_{\alpha}^{\beta} dx \int_{\alpha}^{\beta} dx'|h( x',x)|^2< \infty" /></a>

Integral operators for which this condition is satisfied are called *Hilbert-Schmidt opetators* 

(underconstruct... not really understand the detail)

**Inverse operators**

Only ***H*** operators have no null space.
If ***H*** is one-to-one , we can define an iverse operator <a href="https://www.codecogs.com/eqnedit.php?latex=\mathcal{H}_{L}^{-1}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathcal{H}_{L}^{-1}" title="\mathcal{H}_{L}^{-1}" /></a>
such that 
<a href="https://www.codecogs.com/eqnedit.php?latex=\mathcal{H}_{L}^{-1}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathcal{H}_{L}^{-1}" title="\mathcal{H}_{L}^{-1}" /></a> ***H*****f** = **f**

- <a href="https://www.codecogs.com/eqnedit.php?latex=\mathcal{H}_{L}^{-1}&space;\mathcal{H}&space;=&space;\mathcal{I}_\mathbb{U}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathcal{H}_{L}^{-1}&space;\mathcal{H}&space;=&space;\mathcal{I}_\mathbb{U}" title="\mathcal{H}_{L}^{-1} \mathcal{H} = \mathcal{I}_\mathbb{U}" /></a>       ...(1)
- <a href="https://www.codecogs.com/eqnedit.php?latex=\mathcal{H}\mathcal{H}_{R}^{-1}&space;=&space;\mathcal{I}_\mathbb{V}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathcal{H}\mathcal{H}_{R}^{-1}&space;=&space;\mathcal{I}_\mathbb{V}" title="\mathcal{H}\mathcal{H}_{R}^{-1} = \mathcal{I}_\mathbb{V}" /></a>              ...(2)

In summary, a one-to-one operator always possesses a left inverse satisfying
(1), while an operator that is onto always possesses a right inverse satisfying
(2). We shall use the term inverse, without further qualification, only when
(1) and (2) are both satisfied.


**Adjoint operators**

(empty)

**Projection operators**

(empty)