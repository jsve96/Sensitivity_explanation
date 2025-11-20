## Shows the sensitivity of explanations from Algorithm 1 to changes in the number of dimensions $d$, the number of samples $N$, the number of random projections $L$, and the quantile level $q$.

Default parameters are $N=500, L=1000,q=0.95,d=50$, the underlying stream consists of two Mixture distributions (Gaussian/Exponential 50/50) with means randomly sampled in $(-3,3)$ and variance $I_d$. We randomly select 5/10/15 components for which the mean is randomly changed by an offset uniformly sampled in $(-1,1)$.
### 1) Dimension

![](/imgs/dim.png)

### 2) Samples

![](/imgs/Samples.png)

### 3) Projections

![](/imgs/L.png)

### 4) Quantile

![](/imgs/q.png)
